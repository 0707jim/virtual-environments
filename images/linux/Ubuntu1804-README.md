| Announcements |
|-|
| [Ubuntu 16.04 environment will be removed on September 20, 2021](https://github.com/actions/virtual-environments/issues/3287) |
***
# Ubuntu 18.04.6 LTS
- Linux kernel version: 5.4.0-1059-azure
- Image Version: 20211011.1

## Installed Software
### Language and Runtime
- Bash 4.4.20(1)-release
- Clang 9.0.0
- Clang-format 9.0.0
- Erlang 24.0.5 (Eshell 12.0.3)
- Erlang rebar3 3.17.0
- GNU C++ 7.5.0, 9.4.0, 10.3.0
- GNU Fortran 7.5.0, 9.4.0, 10.3.0
- Julia 1.6.3
- Kotlin 1.5.31-release-548
- Mono 6.12.0.122 (apt source repository: https://download.mono-project.com/repo/ubuntu stable-bionic main)
- MSBuild 16.6.0.15201 (from /usr/lib/mono/msbuild/15.0/bin/MSBuild.dll)
- Node 14.18.0
- Perl 5.26.1
- Python 2.7.17
- Python3 3.6.9
- Ruby 2.5.1p57
- Swift 5.5

### Package Management
- cpan 1.64
- Helm 3.7.0
- Homebrew 3.2.15
- Miniconda 4.10.3
- Npm 6.14.15
- Pip 9.0.1
- Pip3 9.0.1
- Pipx 0.16.4
- RubyGems 2.7.6
- Vcpkg  (build from master \<973a7d5>)
- Yarn 1.22.15

#### Environment variables
| Name                    | Value                  |
| ----------------------- | ---------------------- |
| CONDA                   | /usr/share/miniconda   |
| VCPKG_INSTALLATION_ROOT | /usr/local/share/vcpkg |

### Project Management
- Ant 1.10.5
- Gradle 7.2
- Maven 3.8.3
- Sbt 1.5.5

### Tools
- Ansible 2.11.5
- apt-fast 1.9.11
- AzCopy 10.12.2 (available by `azcopy` and `azcopy10` aliases)
- Bazel 4.2.1
- Bazelisk 1.10.1
- Bicep 0.4.613
- Buildah 1.19.6 (apt source repository: https://download.opensuse.org/repositories/devel:/kubic:/libcontainers:/stable)
- CMake 3.21.3
- CodeQL Action Bundle 2.6.3
- Docker Compose v1 1.29.2
- Docker Compose v2 2.0.0
- Docker-Buildx 0.6.0
- Docker-Moby Client 20.10.9+azure-1
- Docker-Moby Server 20.10.9+azure-1
- Git 2.33.0 (apt source repository: ppa:git-core/ppa)
- Git LFS 2.13.3 (apt source repository: https://packagecloud.io/install/repositories/github/git-lfs)
- Git-ftp 1.3.1
- Haveged 1.9.1
- Heroku 7.59.0
- HHVM (HipHop VM) 4.130.0
- jq 1.5
- Kind 0.11.1
- Kubectl 1.22.2
- Kustomize 4.4.0
- Leiningen 2.9.7
- MediaInfo 17.12
- Mercurial 4.5.3
- Minikube 1.23.2
- Newman 5.3.0
- nvm 0.39.0
- OpenSSL 1.1.1  11 Sep 2018
- Packer 1.7.6
- PhantomJS 2.1.1
- Podman 3.0.1 (apt source repository: https://download.opensuse.org/repositories/devel:/kubic:/libcontainers:/stable)
- Pulumi 3.14.0
- R 4.1.1
- Skopeo 1.2.2 (apt source repository: https://download.opensuse.org/repositories/devel:/kubic:/libcontainers:/stable)
- Sphinx Open Source Search Server 2.2.11
- SVN 1.9.7
- Terraform 1.0.8
- yamllint 1.26.3
- yq 4.13.4
- zstd 1.5.0 (homebrew)

### CLI Tools
- Alibaba Cloud CLI 3.0.94
- AWS CLI 1.20.58
- AWS CLI Session manager plugin 1.2.245.0
- AWS SAM CLI 1.33.0
- Azure CLI (azure-cli) 2.28.0 (installation method: https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-linux?pivots=apt)
- Azure CLI (azure-devops) 0.20.0
- GitHub CLI 2.0.0
- Google Cloud SDK 360.0.0 (apt source repository: https://packages.cloud.google.com/apt)
- Hub CLI 2.14.2
- Netlify CLI 6.10.4
- OpenShift CLI 4.8.13
- ORAS CLI 0.12.0
- Vercel CLI 23.1.2

### Java
| Version             | Vendor        | Environment Variable |
| ------------------- | ------------- | -------------------- |
| 8.0.292+1 (default) | Adopt OpenJDK | JAVA_HOME_8_X64      |
| 11.0.11+9           | Adopt OpenJDK | JAVA_HOME_11_X64     |
| 12.0.2+10           | Adopt OpenJDK | JAVA_HOME_12_X64     |

### PHP
| Tool     | Version                            |
| -------- | ---------------------------------- |
| PHP      | 7.1.33 7.2.34 7.3.31 7.4.24 8.0.11 |
| Composer | 2.1.9                              |
| PHPUnit  | 8.5.21                             |
```
    Both Xdebug and PCOV extensions are installed, but only Xdebug is enabled.
```
### Haskell
- Cabal 3.4.1.0
- GHC 9.0.1
- GHCup 0.1.17.2
- Stack 2.7.3

### Rust Tools
- Cargo 1.55.0
- Rust 1.55.0
- Rustdoc 1.55.0
- Rustup 1.24.3

#### Packages
- Bindgen 0.59.1
- Cargo audit 0.15.2
- Cargo clippy 0.1.55
- Cargo outdated 0.9.17
- Cbindgen 0.20.0
- Rustfmt 1.4.37

### Browsers and Drivers
- Google Chrome 94.0.4606.81
- ChromeDriver 94.0.4606.61
- Mozilla Firefox 93.0
- Geckodriver 0.30.0
- Chromium 94.0.4606.0

#### Environment variables
| Name            | Value                          |
| --------------- | ------------------------------ |
| CHROMEWEBDRIVER | /usr/local/share/chrome_driver |
| GECKOWEBDRIVER  | /usr/local/share/gecko_driver  |

### .NET Core SDK
- 2.1.302 2.1.403 2.1.526 2.1.617 2.1.701 2.1.818 3.1.119 3.1.202 3.1.302 3.1.413 5.0.104 5.0.207 5.0.303 5.0.401

### Databases
- MongoDB 5.0.3 (apt source repository: https://repo.mongodb.org/apt/ubuntu)
- PostgreSQL 14.0 (apt source repository: https://apt.postgresql.org/pub/repos/apt/)
- sqlite3 3.22.0

#### MySQL
- MySQL 5.7.35
- MySQL Server (user:root password:root)

```
    MySQL service is disabled by default. Use the following command as a part of your job to start the service: 'sudo systemctl start mysql.service'
```
#### MS SQL Server Client Tools
- sqlcmd 17.8.0001.1
- SqlPackage 15.0.5282.3

### Cached Tools
#### Go
- 1.13.15
- 1.14.15
- 1.15.15
- 1.16.9
- 1.17.2

#### Node.js
- 10.24.1
- 12.22.6
- 14.18.0

#### PyPy
- 2.7.18 [PyPy 7.3.5]
- 3.6.12 [PyPy 7.3.3]

#### Python
- 2.7.18
- 3.5.10
- 3.6.15
- 3.7.12
- 3.8.12
- 3.9.7

#### Ruby
- 2.4.10
- 2.5.9
- 2.6.8
- 2.7.4
- 3.0.2

#### Environment variables
| Name            | Value                               | Architecture |
| --------------- | ----------------------------------- | ------------ |
| GOROOT_1_13_X64 | /opt/hostedtoolcache/go/1.13.15/x64 | x64          |
| GOROOT_1_14_X64 | /opt/hostedtoolcache/go/1.14.15/x64 | x64          |
| GOROOT_1_15_X64 | /opt/hostedtoolcache/go/1.15.15/x64 | x64          |
| GOROOT_1_16_X64 | /opt/hostedtoolcache/go/1.16.9/x64  | x64          |
| GOROOT_1_17_X64 | /opt/hostedtoolcache/go/1.17.2/x64  | x64          |

### PowerShell Tools
- PowerShell 7.1.4

#### PowerShell Modules
| Module     | Version |
| ---------- | ------- |
| MarkdownPS | 1.9     |
| Pester     | 5.3.1   |

#### Az PowerShell Modules
- 6.4.0 3.1.0.zip 4.4.0.zip 5.9.0.zip

### Web Servers
| Name    | Version | ConfigFile                | ServiceStatus | ListenPort |
| ------- | ------- | ------------------------- | ------------- | ---------- |
| apache2 | 2.4.29  | /etc/apache2/apache2.conf | inactive      | 80         |
| nginx   | 1.14.0  | /etc/nginx/nginx.conf     | inactive      | 80         |

### Android
| Package Name               | Version                                                                                                                                                                                                                                                 |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Android Command Line Tools | 4.0                                                                                                                                                                                                                                                     |
| Android Emulator           | 30.8.4                                                                                                                                                                                                                                                  |
| Android SDK Build-tools    | 31.0.0<br>30.0.0 30.0.1 30.0.2 30.0.3<br>29.0.0 29.0.1 29.0.2 29.0.3<br>28.0.0 28.0.1 28.0.2 28.0.3<br>27.0.0 27.0.1 27.0.2 27.0.3<br>26.0.0 26.0.1 26.0.2 26.0.3<br>25.0.0 25.0.1 25.0.2 25.0.3<br>24.0.0 24.0.1 24.0.2 24.0.3<br>23.0.1 23.0.2 23.0.3 |
| Android SDK Platform-Tools | 31.0.3                                                                                                                                                                                                                                                  |
| Android SDK Platforms      | android-31 (rev 1)<br>android-30 (rev 3)<br>android-29 (rev 5)<br>android-28 (rev 6)<br>android-27 (rev 3)<br>android-26 (rev 2)<br>android-25 (rev 3)<br>android-24 (rev 2)<br>android-23 (rev 3)                                                      |
| Android SDK Tools          | 26.1.1                                                                                                                                                                                                                                                  |
| Android Support Repository | 47.0.0                                                                                                                                                                                                                                                  |
| CMake                      | 3.10.2<br>3.18.1                                                                                                                                                                                                                                        |
| Google APIs                | addon-google_apis-google-21<br>addon-google_apis-google-22<br>addon-google_apis-google-23<br>addon-google_apis-google-24                                                                                                                                |
| Google Play services       | 49                                                                                                                                                                                                                                                      |
| Google Repository          | 58                                                                                                                                                                                                                                                      |
| NDK                        | 21.4.7075529 (default)<br>23.0.7599858                                                                                                                                                                                                                  |
| SDK Patch Applier v4       | 1                                                                                                                                                                                                                                                       |

#### Environment variables
| Name             | Value                                                                                |
| ---------------- | ------------------------------------------------------------------------------------ |
| ANDROID_HOME     | /usr/local/lib/android/sdk                                                           |
| ANDROID_NDK_HOME | /usr/local/lib/android/sdk/ndk-bundle -> /usr/local/lib/android/sdk/ndk/21.4.7075529 |
| ANDROID_NDK_ROOT | /usr/local/lib/android/sdk/ndk-bundle -> /usr/local/lib/android/sdk/ndk/21.4.7075529 |
| ANDROID_SDK_ROOT | /usr/local/lib/android/sdk                                                           |

### Cached Docker images
| Repository:Tag          | Digest                                                                   | Created    |
| ----------------------- | ------------------------------------------------------------------------ | ---------- |
| alpine:3.12             | sha256:a296b4c6f6ee2b88f095b61e95c7ef4f51ba25598835b4978c9256d8c8ace48a  | 2021-08-31 |
| alpine:3.13             | sha256:2582893dec6f12fd499d3a709477f2c0c0c1dfcd28024c93f1f0626b9e3540c8  | 2021-08-31 |
| alpine:3.14             | sha256:e1c082e3d3c45cccac829840a25941e679c25d438cc8412c2fa221cf1a824e6a  | 2021-08-27 |
| buildpack-deps:bullseye | sha256:781dbad21bcc644af42ec465c2adbf6d9470b256755a13b2a2eadadf331cdaf9  | 2021-09-28 |
| buildpack-deps:buster   | sha256:4ab33f2a6712321207d5736d6899841e03d3cc26d50fb7489b0e4a48bf42a1d0  | 2021-09-28 |
| buildpack-deps:stretch  | sha256:57d5d14748554b31c75a2e95e63c51e8cdfb24393e33c1431982123b7d0c2280  | 2021-09-28 |
| debian:10               | sha256:e5cfab8012b17d80f93a7f567797b0c8a2839069d4f50e499152162152518663  | 2021-09-28 |
| debian:11               | sha256:b6a47ddbc1de53e0024d19908f5ef7b3d870686f1234fdb2d19770e097db1575  | 2021-09-28 |
| debian:9                | sha256:c1274c24446b98394e1594ceefac1012e1b39b752586ca993fe3c3bea6f6d20f  | 2021-09-28 |
| moby/buildkit:latest    | sha256:94bc3a93cfa5197064cfdc86e4289cead7b46a2bc95874f142fbf51c67ad2826  | 2021-10-04 |
| node:10                 | sha256:59531d2835edd5161c8f9512f9e095b1836f7a1fcb0ab73e005ec46047384911  | 2021-04-10 |
| node:10-alpine          | sha256:dc98dac24efd4254f75976c40bce46944697a110d06ce7fa47e7268470cf2e28  | 2021-04-14 |
| node:12                 | sha256:86afd89e91d667a65b37e05659974ccd702b8e3b1aff30416d1f77cf67729e2b  | 2021-09-28 |
| node:12-alpine          | sha256:1ea5900145028957ec0e7b7e590ac677797fa8962ccec4e73188092f7bc14da5  | 2021-08-31 |
| node:14                 | sha256:167d0a4af6b4e0d0769086b871a36c25faed75b72705144cabbda70466cc0d8e  | 2021-09-29 |
| node:14-alpine          | sha256:6e52e0b3bedfb494496488514d18bee7fd503fd4e44289ea012ad02f8f41a312  | 2021-09-29 |
| ubuntu:16.04            | sha256:454054f5bbd571b088db25b662099c6c7b3f0cb78536a2077d54adc48f00cd68  | 2021-08-31 |
| ubuntu:18.04            | sha256:bfb4cabd667790ead5c95d9fe341937f0c21118fa79bc768d51c5da9d1dbe917  | 2021-10-01 |
| ubuntu:20.04            | sha256:a0d9e826ab87bd665cfc640598a871b748b4b70a01a4f3d174d4fb02adad07a9  | 2021-10-01 |

### Installed apt packages
| Name              | Version                           |
| ----------------- | --------------------------------- |
| aria2             | 1.33.1-1                          |
| binutils          | 2.30-21ubuntu1\~18.04.5           |
| bison             | 2:3.0.4.dfsg-1build1              |
| brotli            | 1.0.3-1ubuntu1.3                  |
| build-essential   | 12.4ubuntu1                       |
| bzip2             | 1.0.6-8.1ubuntu0.2                |
| coreutils         | 8.28-1ubuntu1                     |
| curl              | 7.58.0-2ubuntu3.16                |
| dbus              | 1.12.2-1ubuntu1.2                 |
| dnsutils          | 1:9.11.3+dfsg-1ubuntu1.15         |
| dpkg              | 1.19.0.5ubuntu2.3                 |
| fakeroot          | 1.22-2ubuntu1                     |
| file              | 1:5.32-2ubuntu0.4                 |
| flex              | 2.6.4-6                           |
| ftp               | 0.17-34                           |
| gnupg2            | 2.2.4-1ubuntu1.4                  |
| haveged           | 1.9.1-6                           |
| imagemagick       | 8:6.9.7.4+dfsg-16ubuntu6.11       |
| iproute2          | 4.15.0-2ubuntu1.3                 |
| iputils-ping      | 3:20161105-1ubuntu3               |
| jq                | 1.5+dfsg-2                        |
| lib32z1           | 1:1.2.11.dfsg-0ubuntu2            |
| libc++-dev        | 6.0-2                             |
| libc++abi-dev     | 6.0-2                             |
| libcurl3          | 7.58.0-2ubuntu3.16                |
| libgbm-dev        | 20.0.8-0ubuntu1\~18.04.1          |
| libgconf-2-4      | 3.2.6-4ubuntu1                    |
| libgsl-dev        | 2.4+dfsg-6                        |
| libgtk-3-0        | 3.22.30-1ubuntu4                  |
| libmagic-dev      | 1:5.32-2ubuntu0.4                 |
| libmagickcore-dev | 8:6.9.7.4+dfsg-16ubuntu6.11       |
| libmagickwand-dev | 8:6.9.7.4+dfsg-16ubuntu6.11       |
| libsecret-1-dev   | 0.18.6-1                          |
| libsqlite3-dev    | 3.22.0-1ubuntu0.4                 |
| libunwind8        | 1.2.1-8                           |
| libxkbfile-dev    | 1:1.0.9-2                         |
| libxss1           | 1:1.2.2-1                         |
| locales           | 2.27-3ubuntu1.4                   |
| m4                | 1.4.18-1                          |
| mediainfo         | 17.12-1                           |
| net-tools         | 1.60+git20161116.90da8a0-1ubuntu1 |
| netcat            | 1.10-41.1                         |
| openssh-client    | 1:7.6p1-4ubuntu0.5                |
| p7zip-full        | 16.02+dfsg-6                      |
| p7zip-rar         | 16.02-2                           |
| parallel          | 20161222-1                        |
| pass              | 1.7.1-3                           |
| patchelf          | 0.9-1                             |
| pkg-config        | 0.29.1-0ubuntu2                   |
| pollinate         | 4.33-0ubuntu1\~18.04.2            |
| python-setuptools | 39.0.1-2                          |
| rpm               | 4.14.1+dfsg1-2                    |
| rsync             | 3.1.2-2.1ubuntu1.1                |
| shellcheck        | 0.4.6-1                           |
| sphinxsearch      | 2.2.11-2                          |
| sqlite3           | 3.22.0-1ubuntu0.4                 |
| ssh               | 1:7.6p1-4ubuntu0.5                |
| sshpass           | 1.06-1                            |
| subversion        | 1.9.7-4ubuntu1                    |
| sudo              | 1.8.21p2-3ubuntu1.4               |
| swig              | 3.0.12-1                          |
| telnet            | 0.17-41                           |
| texinfo           | 6.5.0.dfsg.1-2                    |
| time              | 1.7-25.1build1                    |
| tk                | 8.6.0+9                           |
| tzdata            | 2021a-2ubuntu0.18.04              |
| unzip             | 6.0-21ubuntu1.1                   |
| upx               | 3.94-4                            |
| wget              | 1.19.4-1ubuntu2.2                 |
| xorriso           | 1.4.8-3                           |
| xvfb              | 2:1.19.6-1ubuntu4.9               |
| xz-utils          | 5.2.2-1.3                         |
| zip               | 3.0-11build1                      |
| zsync             | 0.6.2-3ubuntu1                    |


