# Blockchain game

Graduation project

## Installation

1. Install Truffle globally.
    ```javascript
    npm install -g truffle
    ```
    
    1.2 If you are using Window10 and npm>7 then use an older version of truffle. (Otherwise I have problems during installation)
      ```javascript
      npm install -g truffle
      ```
    
2. Download the box. This also takes care of installing the necessary dependencies.
    ```bash
    git clone https://github.com/lonleylokle/blockchain_game.git
    ```
3. Launch Ethereum test net in Ganache.

4. Run the development console.
    ```javascript
    truffle develop
    ```

5. Compile and migrate the smart contracts. Note inside the development console we don't preface commands with `truffle`.
    ```javascript
    compile
    migrate
    ```

6. Run the `liteserver` development server (outside the development console) for front-end hot reloading. Smart contract changes must be manually recompiled and migrated.
    ```javascript
    // Serves the front-end on http://localhost:3000
    npm run dev
    ```
