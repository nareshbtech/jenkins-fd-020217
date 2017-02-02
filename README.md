

# Install Jenkins

- Install key
  ` wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -`

- Added repository
  `vim  /etc/apt/sources.list.d/jenkins.list`
  add deb https://pkg.jenkins.io/debian-stable binary/
  
- Update cache
  `apt-get update -y`

- Install Jenkins 
  `apt-get install jenkin -y`
