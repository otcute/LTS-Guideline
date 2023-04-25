# Setup VScode

---
### I. Install tool

#### 1. Install VScode

+ [Download](https://code.visualstudio.com/download)

#### 2. Install NodeJS v:16.9.1

+ [Install](https://nodejs.org/dist/v16.9.1/node-v16.9.1-x64.msi)

#### 3. Install npm
```
npm install -g npm
```
#### 4. Install Yarn
```
npm install --global yarn
```
#### 5. Install Gitbash
+ [Install](https://git-scm.com/download/win)

### II. Clone code from github

#### Step 1. Login github:
+ Link: 
```
https://github.com/
```
+ Fill username and password
> Username:
```
thuctaplotus@gmail.com
```
> Password:
```
Lotus8888@
```
#### Step 2. Create `LTS` folder at `D` local-disk
#### Step 3. Open `LTS` folder, then right-click, choose `Git Bash Here` option.
#### Step 4. Copy and paste the text below:
```
git clone https://github.com/ltsgroup/ltsgroup-frontend.git
```
Then `Enter`.
### III. Configure environment

#### 1. Create .env.local file at ltsgroup-frontend folder and copy the text below:
```
NEXT_PUBLIC_GRAPHQL_URL=http://172.16.8.20:8080/graphql/
NEXT_PUBLIC_CATEGORY_CAT_EN=blogs,uncategorized
NEXT_PUBLIC_CATEGORY_CAT_KO=test-kr2,test-cate-kr
NEXT_PUBLIC_CATEGORY_CAT_JA=quisquam-2,test-jp,test-abc
NEXT_PUBLIC_FRONT_URL=http://localhost:3000
NEXT_PUBLIC_ENV=dev
```

#### 2. Configure your Git username/email in terminal of VScode:

##### Set your username:
```
git config --global user.name "nameAccount"
```
##### Set your email address:
```
git config --global user.email "youremail@example.com"
```
