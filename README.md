## Instructions

### Step 1: Download Assignment Files

Download the assignment files from the provided link.

### Step 2: Check Node.js Installation

Check if Node.js is installed on your computer. If not, Install with "sudo apt install nodejs" command.

### Step 3: Install Dependencies

Run the following command to install dependencies:
command - "npm install"
This will generate node_modules and package-lock.json.

### Step 4: Run this Program Loacally 

Command - "node main.js"

### Step 5: Create Dockerfile

### Step 6: Build Docker image

command - "docker build -t node-app ."

### Step 7: Run Docker Container

command - "docker run -d -p 3000:3000 node-app"

### Step 8: Access API

Access the API at http://localhost:3000 and you should see the response "Hello, World!".

### BOUNUS STEP

write a docker-compose file ---
- Run following Command to start container
  command - "docker-compose up -d

