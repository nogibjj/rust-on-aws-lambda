# Rust-on-AWS-Lambda

```bash
cargo init

cargo build --release --target=x86_64-unknown-linux-gnu

cp target/x86_64-unknown-linux-gnu/release/[Name of the app] ./bootstrap

```


```bash
sudo apt install curl

curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -

sudo apt-get install -y nodejs

sudo npm install -g serverless

serverless deploy
# https://kinsta.com/blog/how-to-install-node-js/

curl -i https://jd39a221u3.execute-api.us-east-1.amazonaws.com/dev/pizza/[pizza name]/price
#veggie, regina, deluxe
```

## References
* [RUST on AWS Lambda | TDD live coding | Build a 🍕 API | No talking](https://www.youtube.com/watch?v=Idys2BAmqIU)
* [how-to-install-node-js](https://kinsta.com/blog/how-to-install-node-js/)
* [aws-credentials](https://www.serverless.com/framework/docs/providers/aws/guide/credentials)
* [rust-cli-template](https://github.com/kbknapp/rust-cli-template)