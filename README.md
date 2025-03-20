# aws-infra-atividade                                                                                                                                                                                                         

## Descriçã odo terminal criando arquivo .env containers rodando 

[ec2-user@ip-172-31-91-108 ~]$ git clone https://github.com/vitormendes09/API_AWS.git
Cloning into 'API_AWS'...
remote: Enumerating objects: 104, done.
remote: Counting objects: 100% (104/104), done.
remote: Compressing objects: 100% (79/79), done.
remote: Total 104 (delta 18), reused 99 (delta 13), pack-reused 0 (from 0)
Receiving objects: 100% (104/104), 1.71 MiB | 27.82 MiB/s, done.
Resolving deltas: 100% (18/18), done.
[ec2-user@ip-172-31-91-108 ~]$ ls
API_AWS
[ec2-user@ip-172-31-91-108 ~]$ nano .env
[ec2-user@ip-172-31-91-108 ~]$ ls -la
total 32
drwx------. 4 ec2-user ec2-user   115 Mar 20 15:01 .
drwxr-xr-x. 4 root     root        38 Mar 20 14:53 ..
-rw-r--r--. 1 ec2-user ec2-user    18 Jan 28  2023 .bash_logout
-rw-r--r--. 1 ec2-user ec2-user   141 Jan 28  2023 .bash_profile
-rw-r--r--. 1 ec2-user ec2-user   492 Jan 28  2023 .bashrc
-rw-------. 1 ec2-user ec2-user     5 Mar 20 14:58 .node_repl_history
drwx------. 2 ec2-user ec2-user    29 Mar 20 14:50 .ssh
drwxrwxr-x. 9 ec2-user ec2-user 16384 Mar 20 15:01 API_AWS
[ec2-user@ip-172-31-91-108 ~]$ cd API_AWS/
[ec2-user@ip-172-31-91-108 API_AWS]$ ls -la
total 180
drwxrwxr-x. 9 ec2-user ec2-user 16384 Mar 20 15:01 .
drwx------. 4 ec2-user ec2-user   115 Mar 20 15:01 ..
-rw-rw-r--. 1 ec2-user ec2-user    52 Mar 20 15:01 .dockerignore
drwxrwxr-x. 8 ec2-user ec2-user   163 Mar 20 15:01 .git
-rw-rw-r--. 1 ec2-user ec2-user    19 Mar 20 15:01 .gitignore
-rw-rw-r--. 1 ec2-user ec2-user    97 Mar 20 15:01 Dockerfile
-rw-rw-r--. 1 ec2-user ec2-user   550 Mar 20 15:01 README.md
-rw-rw-r--. 1 ec2-user ec2-user   390 Mar 20 15:01 cli.rest
drwxrwxr-x. 5 ec2-user ec2-user    85 Mar 20 15:01 dist
-rw-rw-r--. 1 ec2-user ec2-user   453 Mar 20 15:01 docker-compose.api.yml
-rw-rw-r--. 1 ec2-user ec2-user  1222 Mar 20 15:01 docker-compose.yml
-rw-rw-r--. 1 ec2-user ec2-user   358 Mar 20 15:01 middleware.js
drwxrwxr-x. 2 ec2-user ec2-user    21 Mar 20 15:01 models
-rw-rw-r--. 1 ec2-user ec2-user   138 Mar 20 15:01 nodemon.json
-rw-rw-r--. 1 ec2-user ec2-user  1209 Mar 20 15:01 old.docker-compose.yml
-rw-rw-r--. 1 ec2-user ec2-user 58094 Mar 20 15:01 package-lock.json
-rw-rw-r--. 1 ec2-user ec2-user   817 Mar 20 15:01 package.json
-rw-rw-r--. 1 ec2-user ec2-user 34677 Mar 20 15:01 pnpm-lock.yaml
drwxrwxr-x. 3 ec2-user ec2-user   136 Mar 20 15:01 scripts
-rw-rw-r--. 1 ec2-user ec2-user  2093 Mar 20 15:01 server.js
drwxrwxr-x. 6 ec2-user ec2-user    97 Mar 20 15:01 src
drwxrwxr-x. 4 ec2-user ec2-user    30 Mar 20 15:01 static
-rw-rw-r--. 1 ec2-user ec2-user  1065 Mar 20 15:01 system-life.js
-rw-rw-r--. 1 ec2-user ec2-user 12664 Mar 20 15:01 tsconfig.json
drwxrwxr-x. 3 ec2-user ec2-user   102 Mar 20 15:01 views
[ec2-user@ip-172-31-91-108 API_AWS]$ nano .env
[ec2-user@ip-172-31-91-108 API_AWS]$ ls -la
total 180
drwxrwxr-x. 9 ec2-user ec2-user 16384 Mar 20 15:01 .
drwx------. 4 ec2-user ec2-user   115 Mar 20 15:01 ..
-rw-rw-r--. 1 ec2-user ec2-user    52 Mar 20 15:01 .dockerignore
drwxrwxr-x. 8 ec2-user ec2-user   163 Mar 20 15:01 .git
-rw-rw-r--. 1 ec2-user ec2-user    19 Mar 20 15:01 .gitignore
-rw-rw-r--. 1 ec2-user ec2-user    97 Mar 20 15:01 Dockerfile
-rw-rw-r--. 1 ec2-user ec2-user   550 Mar 20 15:01 README.md
-rw-rw-r--. 1 ec2-user ec2-user   390 Mar 20 15:01 cli.rest
drwxrwxr-x. 5 ec2-user ec2-user    85 Mar 20 15:01 dist
-rw-rw-r--. 1 ec2-user ec2-user   453 Mar 20 15:01 docker-compose.api.yml
-rw-rw-r--. 1 ec2-user ec2-user  1222 Mar 20 15:01 docker-compose.yml
-rw-rw-r--. 1 ec2-user ec2-user   358 Mar 20 15:01 middleware.js
drwxrwxr-x. 2 ec2-user ec2-user    21 Mar 20 15:01 models
-rw-rw-r--. 1 ec2-user ec2-user   138 Mar 20 15:01 nodemon.json
-rw-rw-r--. 1 ec2-user ec2-user  1209 Mar 20 15:01 old.docker-compose.yml
-rw-rw-r--. 1 ec2-user ec2-user 58094 Mar 20 15:01 package-lock.json
-rw-rw-r--. 1 ec2-user ec2-user   817 Mar 20 15:01 package.json
-rw-rw-r--. 1 ec2-user ec2-user 34677 Mar 20 15:01 pnpm-lock.yaml
drwxrwxr-x. 3 ec2-user ec2-user   136 Mar 20 15:01 scripts
-rw-rw-r--. 1 ec2-user ec2-user  2093 Mar 20 15:01 server.js
drwxrwxr-x. 6 ec2-user ec2-user    97 Mar 20 15:01 src
drwxrwxr-x. 4 ec2-user ec2-user    30 Mar 20 15:01 static
-rw-rw-r--. 1 ec2-user ec2-user  1065 Mar 20 15:01 system-life.js
-rw-rw-r--. 1 ec2-user ec2-user 12664 Mar 20 15:01 tsconfig.json
drwxrwxr-x. 3 ec2-user ec2-user   102 Mar 20 15:01 views
[ec2-user@ip-172-31-91-108 API_AWS]$ nano .env
[ec2-user@ip-172-31-91-108 API_AWS]$ ls -la
total 184
drwxrwxr-x. 9 ec2-user ec2-user 16384 Mar 20 15:22 .
drwx------. 4 ec2-user ec2-user   115 Mar 20 15:01 ..
-rw-rw-r--. 1 ec2-user ec2-user    52 Mar 20 15:01 .dockerignore
-rw-rw-r--. 1 ec2-user ec2-user   185 Mar 20 15:22 .env
drwxrwxr-x. 8 ec2-user ec2-user   163 Mar 20 15:01 .git
-rw-rw-r--. 1 ec2-user ec2-user    19 Mar 20 15:01 .gitignore
-rw-rw-r--. 1 ec2-user ec2-user    97 Mar 20 15:01 Dockerfile
-rw-rw-r--. 1 ec2-user ec2-user   550 Mar 20 15:01 README.md
-rw-rw-r--. 1 ec2-user ec2-user   390 Mar 20 15:01 cli.rest
drwxrwxr-x. 5 ec2-user ec2-user    85 Mar 20 15:01 dist
-rw-rw-r--. 1 ec2-user ec2-user   453 Mar 20 15:01 docker-compose.api.yml
-rw-rw-r--. 1 ec2-user ec2-user  1222 Mar 20 15:01 docker-compose.yml
-rw-rw-r--. 1 ec2-user ec2-user   358 Mar 20 15:01 middleware.js
drwxrwxr-x. 2 ec2-user ec2-user    21 Mar 20 15:01 models
-rw-rw-r--. 1 ec2-user ec2-user   138 Mar 20 15:01 nodemon.json
-rw-rw-r--. 1 ec2-user ec2-user  1209 Mar 20 15:01 old.docker-compose.yml
-rw-rw-r--. 1 ec2-user ec2-user 58094 Mar 20 15:01 package-lock.json
-rw-rw-r--. 1 ec2-user ec2-user   817 Mar 20 15:01 package.json
-rw-rw-r--. 1 ec2-user ec2-user 34677 Mar 20 15:01 pnpm-lock.yaml
drwxrwxr-x. 3 ec2-user ec2-user   136 Mar 20 15:01 scripts
-rw-rw-r--. 1 ec2-user ec2-user  2093 Mar 20 15:01 server.js
drwxrwxr-x. 6 ec2-user ec2-user    97 Mar 20 15:01 src
drwxrwxr-x. 4 ec2-user ec2-user    30 Mar 20 15:01 static
-rw-rw-r--. 1 ec2-user ec2-user  1065 Mar 20 15:01 system-life.js
-rw-rw-r--. 1 ec2-user ec2-user 12664 Mar 20 15:01 tsconfig.json
drwxrwxr-x. 3 ec2-user ec2-user   102 Mar 20 15:01 views
[ec2-user@ip-172-31-91-108 API_AWS]$ docker compose --env-file ./.env up -d
[+] Running 27/27
 ✔ aws_psql 9 layers [⣿⣿⣿⣿⣿⣿⣿⣿⣿]      0B/0B      Pulled                                19.9s
   ✔ d8d8fb695a5a Pull complete                                                         4.7s
   ✔ c24c1ba610df Pull complete                                                         5.1s
   ✔ 83efd74bc97e Pull complete                                                         5.4s
   ✔ 215ba3ecdc26 Pull complete                                                         7.1s
   ✔ 15ca4c67ed92 Pull complete                                                         6.0s
   ✔ 4f18957d9158 Pull complete                                                         6.2s
   ✔ 404c53e09e31 Pull complete                                                         6.3s
   ✔ 9e4acb9ca7d3 Pull complete                                                         6.4s
   ✔ 8f4971a5dfe7 Pull complete                                                         6.4s
 ✔ pgadmin4 16 layers [⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿]      0B/0B      Pulled                        22.9s
   ✔ f18232174bc9 Pull complete                                                         0.3s
   ✔ baf15215d437 Pull complete                                                         5.8s
   ✔ 10310706b407 Pull complete                                                         0.5s
   ✔ ff532a74538f Pull complete                                                         0.5s
   ✔ b3609372ed79 Pull complete                                                         0.8s
   ✔ 7ac647b180d0 Pull complete                                                         0.7s
   ✔ 09b82c77e4b0 Pull complete                                                         0.8s
   ✔ bc9f31d99706 Pull complete                                                         0.9s
   ✔ f0fb1842f0c3 Pull complete                                                         2.2s
   ✔ 2dc7afb132e7 Pull complete                                                         4.5s
   ✔ 380cf8e4f913 Pull complete                                                         2.4s
   ✔ 236726433656 Pull complete                                                         2.6s
   ✔ 0695f25b9342 Pull complete                                                         2.8s
   ✔ b74202090be6 Pull complete                                                         3.0s
   ✔ 669ceba5e652 Pull complete                                                         3.2s
   ✔ 6b5b0437a91d Pull complete                                                         6.1s
[+] Building 32.2s (10/10) FINISHED                                           docker:default
 => [app internal] load build definition from Dockerfile                                0.1s
 => => transferring dockerfile: 189B                                                    0.0s
 => [app internal] load metadata for docker.io/library/node:latest                      0.4s
 => [app internal] load .dockerignore                                                   0.0s
 => => transferring context: 147B                                                       0.0s
 => [app 1/5] FROM docker.io/library/node:latest@sha256:990d0ab35ae15d8a322ee1eeaf4f7  25.4s
 => => resolve docker.io/library/node:latest@sha256:990d0ab35ae15d8a322ee1eeaf4f7cf14e  0.0s
 => => sha256:b1e1dcf10eb99d81bb7a6a3b3eeee38350a171fec38ac43a722639e3 6.39kB / 6.39kB  0.0s
 => => sha256:7cd785773db44407e20a679ce5439222e505475eed5b99f1910eb2 48.47MB / 48.47MB  1.9s
 => => sha256:091eb8249475f42de217265c501e0186f0a3ea7490ef7f51458c30 24.01MB / 24.01MB  1.1s
 => => sha256:255774e0027b72d2327719e78dbad5ad8c9cf446d055e45be7fc14 64.40MB / 64.40MB  3.2s
 => => sha256:990d0ab35ae15d8a322ee1eeaf4f7cf14e367d3d0ee2f472704b7b3d 6.41kB / 6.41kB  0.0s
 => => sha256:c591a421f28fc30b6fdaa9ab71f75284a5ac658cd44405f3a9d14f2d 2.49kB / 2.49kB  0.0s
 => => sha256:353e14e5cc47664fba714a7da288001d90427c705494847ac773 211.35MB / 211.35MB  7.4s
 => => extracting sha256:7cd785773db44407e20a679ce5439222e505475eed5b99f1910eb2cda5172  5.1s
 => => sha256:fe9c928bbad8122f017915d1fe7235a06aa6f607d492c4e12bcc6cdb 3.33kB / 3.33kB  2.0s
 => => sha256:2d0f54eac651d47feed1bda2a410bb86758b1e1833be08e1dc9ec2 57.50MB / 57.50MB  4.9s
 => => sha256:baf25547952506604483c768c35925839fc5226750765f33e711aaf4 1.25MB / 1.25MB  3.3s
 => => sha256:b0cb542452c616d345e6352a8eefc84057d9f3cefe75ac7a7c7c85f4100e 446B / 446B  3.4s
 => => extracting sha256:091eb8249475f42de217265c501e0186f0a3ea7490ef7f51458c30db91fb3  0.9s
 => => extracting sha256:255774e0027b72d2327719e78dbad5ad8c9cf446d055e45be7fc149418470  3.5s
 => => extracting sha256:353e14e5cc47664fba714a7da288001d90427c705494847ac773f5cc08199  9.5s
 => => extracting sha256:fe9c928bbad8122f017915d1fe7235a06aa6f607d492c4e12bcc6cdb74b65  0.0s
 => => extracting sha256:2d0f54eac651d47feed1bda2a410bb86758b1e1833be08e1dc9ec27aa8d66  3.4s
 => => extracting sha256:baf25547952506604483c768c35925839fc5226750765f33e711aaf4dc1d3  0.1s
 => => extracting sha256:b0cb542452c616d345e6352a8eefc84057d9f3cefe75ac7a7c7c85f4100e3  0.0s
 => [app internal] load build context                                                   0.5s
 => => transferring context: 4.87MB                                                     0.5s
 => [app 2/5] WORKDIR /app                                                              0.2s
 => [app 3/5] COPY package*.json ./                                                     0.1s
 => [app 4/5] RUN npm install                                                           4.5s
 => [app 5/5] COPY . .                                                                  0.2s
 => [app] exporting to image                                                            1.2s
 => => exporting layers                                                                 1.2s
 => => writing image sha256:858fd553eaf03cdd78de33081be91129a4694d5237da212cdb7a330ad3  0.0s
 => => naming to docker.io/library/api_aws-app                                          0.0s
[+] Running 5/5
 ✔ Network api_aws_aws-network  Created                                                 0.1s
 ✔ Volume "api_aws_pg-data"     Created                                                 0.0s
 ✔ Container postgres           Started                                                 0.1s
 ✔ Container aws_app            Started                                                 0.0s
 ✔ Container pgadmin_container  Started                                                 0.1s
[ec2-user@ip-172-31-91-108 API_AWS]$ docker container ps -a
CONTAINER ID   IMAGE             COMMAND                  CREATED          STATUS          PORTS                                            NAMES
ef2fef487253   dpage/pgadmin4    "/entrypoint.sh"         49 seconds ago   Up 47 seconds   443/tcp, 0.0.0.0:8080->80/tcp, :::8080->80/tcp   pgadmin_container
a320c674471c   api_aws-app       "docker-entrypoint.s…"   49 seconds ago   Up 47 seconds   0.0.0.0:3001->3001/tcp, :::3001->3001/tcp        aws_app
e462f54f9cbc   postgres:alpine   "docker-entrypoint.s…"   49 seconds ago   Up 47 seconds   0.0.0.0:5432->5432/tcp, :::5432->5432/tcp        postgres
[ec2-user@ip-172-31-91-108 API_AWS]$
