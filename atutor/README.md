You can download the vulnerable version from here.

- https://sourceforge.net/projects/atutor/files/atutor_2_2_1/
- https://www.exploit-db.com/exploits/39514
- https://www.exploit-db.com/exploits/39639

You need XAMPP 1.8.3-5 which uses PHP 5. You can direct download from first link or check second link

- https://sourceforge.net/projects/xampp/files/XAMPP%20Linux/1.8.3/xampp-linux-x64-1.8.3-5-installer.run/download
- https://sourceforge.net/projects/xampp/files/XAMPP%20Linux/1.8.3/

Once file is downloaded place in same directory as docker file as `xampp.run`.

During the ATutor installation, you might need to go inside container and fix permissions if needed, I do not bother to fix in Dockerfile atm.

```bash
docker exec -it atutor-mysql /bin/bash
```
