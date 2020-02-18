# Database Schema  
CREATE TABLE CORP_MASTER  
(  
    CM_CORP_ID INT,  
    CM_ACT INT,  
    CM_STATUS INT,  
    CM_BN TEXT,  
    CM_DIRECTOR_MIN INT,  
    CM_DIRECTOR_MAX INT,  
    CM_CTRLDATE DATE,  
    PRIMARY KEY (CM_CORP_ID)  
);  


CREATE TABLE corp_id(ci_corp_id int);  

CREATE TABLE IF NOT EXISTS "corp_info"(  
  ci_corp_id INT,  
  ci_name TEXT,  
  ci_lab TEXT,  
  ci_text TEXT  
);  

CREATE TABLE directors(  
  ci_corp_id INT,  
  ci_name TEXT,  
  ci_lab TEXT,  
  ci_text TEXT  
);  
