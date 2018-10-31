# Deploy using Github and AWS EC2/S3
The basic way to deploy React App via Github and AWS

<p align="center">
  <img width="80%" src="./DeployBasic.png">
  <br>Deploy using EC2 and S3 of AWS
</p>

## Deploy Sequence with Command-line Interface
<b>1. Create-react-app</b><br>
React project development<br>

<b>2. Webpack do minimization, make predeploy files at /build folder</b><br>
```
$yarn build
```
<b>3. [AWS EC2 Node web server construct via this way](http://cinema4dr12.tistory.com/741)</b><br>

<b>4. Run with basic server: serve</b><br>
serve? using static server for environment using Node<br>
```
$npm install -g serve
$serve -s build
```
*ref. [Ways of Deployment](https://facebook.github.io/create-react-app/docs/deployment)<br>
