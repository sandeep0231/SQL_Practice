CREATE TABLE Employee (
    id INT primary_key AUTO_INCREMENT,
    name VARCHAR(255),
    emailid VARCHAR(256),
    code VARCHAR(256),
   salary DECIMAL(10, 2),
    role_id INT,
    role VARCHAR(256),
    status INT
);

INSERT INTO Employee (id,name, emailid, code, role_id, role, status, salary) VALUES
(1,'John Doe', 'john.doe@example.com', 'JD123', 1, 'Admin', 1, 50000.00),
(2,'Jane Smith', 'jane.smith@example.com', 'JS456', 2, 'User', 1, 60000.50),
(3,'Michael Brown', 'michael.brown@example.com', 'MB789', 3, 'Editor', 0, 75000.75),
(4,'Emily Johnson', 'emily.johnson@example.com', 'EJ987', 2, 'User', 1, 55000.25),
(5,'David Lee', 'david.lee@example.com', 'DL654', 1, 'Admin', 0, 48000.00);
