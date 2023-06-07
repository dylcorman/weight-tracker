# WeightMaster

WeightMaster is a web application that allows users to easily track their weight measurements over time. It provides a simple and intuitive user interface for adding, viewing, editing, and deleting measurements, making it easy to keep track of your health and fitness progress.

## Features

- Secure user registration and login using Okta
- Ability to add new weight measurements with associated dates
- View a list of all past measurements
- Update existing weight measurements
- Delete measurements

## Installation and Setup

1. Clone the repository
    ```
    git clone https://github.com/<your-username>/WeightMaster.git
    cd WeightMaster
    ```

2. Install the dependencies
    ```
    npm install
    ```

3. Create a `.env` file in the root of your project and insert your key-value pairs in the following format:
    ```shell
    KEY=VALUE
    ```
    Here's an example:
    ```shell
    PORT=8080
    HOST=localhost
    NODE_ENV=development
    HOST_URL=http://localhost:8080
    COOKIE_ENCRYPT_PWD=superAwesomePasswordStringThatIsAtLeast32CharactersLong!
    OKTA_ORG_URL=https://dev-97079945.okta.com
    OKTA_CLIENT_ID=0oa9uz7pfcXznm15V5d7
    OKTA_CLIENT_SECRET=y4Wea49Xt9UVSmUw4FohpTp5jjR2NCF8wukXBhXz
    PGHOST=localhost
    PGUSERNAME=postgres
    PGDATABASE=postgres
    PGPASSWORD=p@ssw0rd42
    PGPORT=5432
    ```

4. Start the server
    ```
    npm start
    ```

## Usage

After starting the server, navigate to `http://localhost:8080` (or whatever your HOST_URL is set to) in your web browser. Register for an account, or if you already have one, log in to view the dashboard and start tracking your weight.


