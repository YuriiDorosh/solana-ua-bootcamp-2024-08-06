FILE=generate-keypairs.ts

.PHONY npm-init npm-install npm-start npm-start-load-keypairs:

npm-init:
	npm init -y

npm-install:
	npm i @solana/web3.js @solana-developers/helpers esrun 

npm-start:
	npx esrun ${FILE}

npm-start-load-keypairs:
	npx esrun load-keypair.ts