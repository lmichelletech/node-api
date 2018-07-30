const http = require('http');
const port = 3000;
const host = '127.0.0.1';

const server = http.createServer();

server.on('request', (req, res) => {
    const {method, url} = req;
    console.log('method', method, 'url', url);
})

app.listen(port, host, function(){
    
        console.log(`Server running at http://${hostname}:${port}/`);
    
})