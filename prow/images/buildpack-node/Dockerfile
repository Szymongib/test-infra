# Basic node buildpack

FROM eu.gcr.io/kyma-project/prow/bootstrap:0.0.1

RUN curl -sL https://deb.nodesource.com/setup_10.x | bash -
RUN apt-get update && apt-get install -y --no-install-recommends \
    nodejs \
    && apt-get clean

RUN npm install -g eslint-config-react-app@^3.0.4 \
    babel-eslint@^9.0.0 \
    eslint@^5.6.1 \
    eslint-plugin-flowtype@^2.50.3 \
    eslint-plugin-import@^2.14.0 \
    eslint-plugin-jsx-a11y@^6.1.2 \
    eslint-plugin-react@^7.11.1 \
    tslint@^5.11.0 \
    tslint-angular@^1.1.2 \
    tslint-config-prettier@^1.15.0 \
    typescript@^3.1.3 \
    prettier@^1.14.3 \
    whitesource@^18.10.1
