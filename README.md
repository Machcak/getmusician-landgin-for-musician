# getmusician-landgin-for-musician

curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash
command -v nvm
nvm install node
nvm use node

npm install -g live-server
npm install -g sass

clone git@github.com:Machcak/getmusician-landgin-for-musician.git
cd getmusician-landgin-for-musician

live-server
sass --watch scss:css
