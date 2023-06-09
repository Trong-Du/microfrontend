# Building Micro Frontends with React, Vue

FE: React, Vue <br/>
Infra: Github Actions, AWS

## Getting started

1. Clone the repo

```sh
git clone https://github.com/Trong-Du/microfrontend.git
```

2. Install dependencies

```sh
cd packages/auth && yarn
cd packages/container && yarn
cd packages/dashboard && yarn
cd packages/marketing && yarn
```

3. Start the app

```sh
cd packages/auth && yarn start
cd packages/container && yarn start
cd packages/dashboard && yarn start
cd packages/marketing && yarn start
```

4. Visit the following URLS:

```sh
# renders by container
http://localhost:8080/

# renders `marketing` app in isolation
http://localhost:8081

# renders `auth` app in isolation
http://localhost:8082

# renders `dashboard` app in isolation
http://localhost:8083

```

5. [Demo](https://d3uci0y9c52m78.cloudfront.net/)
