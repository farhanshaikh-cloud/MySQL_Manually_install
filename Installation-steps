MySQL Community Edition

  1. Direct download command:
    wget https://dev.mysql.com/get/Downloads/MySQL-9.5/mysql-9.5.0-1.el9.x86_64.rpm-bundle.tar

  2. Then verify
    ls -la
    file mysql-9.5.0-1.el9.x86_64.rpm-bundle.tar

  3. Extract tar downloaded file
    tar -xvf mysql-9.5.0-1.el9.x86_64.rpm-bundle.tar

  4. Install RPMs
    sudo dnf install *.rpm -y

            or

    sudo dnf install mysql-community-server-9.5.0-1.el9.x86_64.rpm \
     mysql-community-client-9.5.0-1.el9.x86_64.rpm \
     mysql-community-common-9.5.0-1.el9.x86_64.rpm \
     mysql-community-libs-9.5.0-1.el9.x86_64.rpm -y

            or 

     sudo dnf localinstall *.rpm -y

  5. Start MySQL Service
      sudo systemctl start mysqld

  6. Enable at boot:
      sudo systemctl enable mysqld

  7. Check Status
      sudo systemctl status mysqld
