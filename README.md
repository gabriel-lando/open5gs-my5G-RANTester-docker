# open5gs-my5G-RANTester-docker
This repository contains the instructions to running Open5GS-CN in version v2.3.6 and my5G-RANTester(a gNB/UE simulator) in version 1.0.0

### Instructions 

## Build the image 
- git clone https://github.com/my5G/open5gs-my5G-RANTester-docker.git
- cd open5gs-my5G-RANTester-docker
- docker build -f nf_tester/Dockerfile --tag my5grantester:latest .

## Execute the tester
- docker-compose up -d 
