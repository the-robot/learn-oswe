You can download the vulnerable version from here.

- https://sourceforge.net/projects/atutor/files/atutor_2_2_1/
- https://www.exploit-db.com/exploits/39514
- https://www.exploit-db.com/exploits/39639

<br/>

## Setup

You need XAMPP 1.8.3-5 which uses PHP 5. You can direct download from first link or check second link

- https://sourceforge.net/projects/xampp/files/XAMPP%20Linux/1.8.3/xampp-linux-x64-1.8.3-5-installer.run/download
- https://sourceforge.net/projects/xampp/files/XAMPP%20Linux/1.8.3/

Once file is downloaded place in same directory as docker file with file name `xampp.run`. You can use the comment below if you need
to go inside the container.

```bash
docker exec -it oswe-atutor /bin/bash
```

Please follow the instruction from the webpage at `localhost:8080/atutor`.

> You can give the following for setup accounts in installation.
> **Administrator:** `admin:admin | admin@offsec.com`
> **Site contact email:** `system@offsec.com`
> **Personal:** `offsec:offsec | offsec@offsec.com`

Default XAMPP credentials for MySQL is `root` and no password.

<br/>

## ATutor 2.2.1

![image](https://github.com/the-robot/OSWE/assets/9334746/b03224fe-f082-453e-b0f4-59ba77b160ff)
