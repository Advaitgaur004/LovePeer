# LovePeer

LovePeer adds real-time communication capabilities to your application, working on top of an open standard. It supports video, voice, and generic data to be sent between peers, enabling developers to build powerful voice and video communication solutions.

## Features

- **Real-time Communication**: Supports video, voice, and data transfer between peers.
- **Open Standard**: Built on top of open standards for ease of integration and flexibility.
- **Scalable**: Can be scaled to fit various application needs, from small-scale personal projects to large enterprise solutions.

## Installation

### Clone the Repository

First, clone the repository from GitHub:

```bash
git clone https://github.com/Advaitgaur004/LovePeer
```

### Moving
Change the directory to the FirebaseRTC folder:
```bash
cd FirebaseRTC
```

### Install Firebase Tools
#### Install Firebase tools globally using npm:

```bash
npm -g install firebase-tools
```

## Setup

### Set up to your Account
```bash
firebase login
```

### Add Firebase Project
```bash
firebase use --add
# Provide an alias for the project
```
### Run locally
```bash
firebase serve --only hosting
```

## Usage

1. **Video Communication**: Integrate video calling features into your application.
2. **Voice Communication**: Add voice chat functionalities.
3. **Data Transfer**: Enable peer-to-peer data transfer for various use cases.

## Contributing

We welcome contributions! Please fork the repository and create a pull request with your changes.

1. Fork the repository
2. Create a new branch: `git checkout -b feature-branch`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature-branch`
5. Submit a pull request
