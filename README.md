<h1 align="center"> 
    RTMP to HLS Server
</h1>


<p align="center">
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000&style=for-the-badge" alt="JavaScript">    
    <img src="https://img.shields.io/badge/Node.js-339933.svg?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge" alt="MIT License">    
</p>

## Table of Contents
1. [Description](#description)
2. [Usage](#usage)
3. [Technologies Used](#technologies-used)
4. [Contact Information](#contact-information)
5. [License](#license)

## Description
A server for handling video streaming from an RTMP client (such as OBS) so that it can be played back in a web browser. The server is built using Node.js and the `node-media-server` package. FFmpeg is used to transcode the video stream to HLS protocol, which can be played back in a web browser. The Windows binary for FFmpeg is included in the repository, and is compressed using UPX to reduce the file size. For other operating systems, you will need to download the FFmpeg binary from the [official website](https://www.ffmpeg.org/) and configure the path in the `server.js` file.

## Usage
To use this server, you will need to have Node.js installed on your machine. You can install Node.js from the [official website](https://nodejs.org/en/). Once you have Node.js installed, you can clone this repository and run the following commands to start the server:

```bash
npm install
npm start
```

This will start the RTMP to HLS server on port 1935. You can then use an RTMP client (such as OBS) to stream video content to the server.

## Technologies Used
* JavaScript
* [Node.js](https://nodejs.org/en/)

## Credits
* [node-media-server](https://www.npmjs.com/package/node-media-server)
* [CORS](https://www.npmjs.com/package/cors)
* [FFmpeg](https://www.ffmpeg.org/)
* [UPX](https://upx.github.io/)

## Contact Information
<p align="center">
    <a href="mailto:cwchilvers@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
    <a href="https://github.com/cwchilvers"><img src="https://img.shields.io/badge/GitHub-181717.svg?style=for-the-badge&logo=GitHub&logoColor=white" alt="GitHub"></a>
</p>

## License
This project is licensed under the MIT License. See the [MIT License](https://opensource.org/licenses/mit/) page for details.
