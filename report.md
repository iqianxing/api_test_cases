#add()  
    √ correctly adds 2 args  
    √ correctly adds 3 args  
    √ correctly adds 4 args  
    
  #ajax  
    √ http://www.qq.com (177ms)  
    √ http://react.apptravel.cn/ (225ms)  
    √ http://react.apptravel.cn/article/20 (183ms)  
    √ https://www.baidu.com/ (67ms)  
    √ http://www.126.com/ (63ms)  
    √ https://segmentfault.com/a/1190000002748032 (412ms)  
    
  #Array  
    ##indexOf()  
      √ should return -1 when the value is not present  
    
  #diff  
    ##toLocaleLowerCase()  
      √ http://www.qq.com  
      √ http://react.apptravel.cn/  
      √ http://react.apptravel.cn/article/20  
      √ https://www.baidu.com/  
      √ http://www.126.com/  
      √ https://segmentfault.com/a/1190000002748032  
    ##equal()  
      √ http://www.qq.com  
      √ http://react.apptravel.cn/  
      √ http://react.apptravel.cn/article/20  
      √ https://www.baidu.com/  
      √ http://www.126.com/  
      √ https://segmentfault.com/a/1190000002748032  
    
  #request  
    √ http://www.qq.com (130ms)  
    √ http://react.apptravel.cn/ (141ms)  
    √ http://react.apptravel.cn/article/20 (167ms)  
    √ https://www.baidu.com/ (42ms)  
    √ http://www.126.com/ (65ms)  
    √ https://segmentfault.com/a/1190000002748032 (387ms)  
    
  #Array  
    ##indexOf()  
      √ should return -1 when the value is not present  
    
  #superagent  
    1) http://www.qq.com  
    2) http://react.apptravel.cn/  
    3) http://react.apptravel.cn/article/20  
    4) https://www.baidu.com/  
    5) http://www.126.com/  
    6) https://segmentfault.com/a/1190000002748032  
    
    
  29 passing (8s)  
  6 failing  
    
  1) #superagent http://www.qq.com:  
      Uncaught TypeError: Cannot read property 'statusCode' of undefined  
      at test\test_superagent.js:20:38  
      at Request.callback (node_modules\superagent\lib\node\index.js:687:3)  
      at ClientRequest.<anonymous> (node_modules\superagent\lib\node\index.js:615:10)  
      at Socket.socketErrorListener (_http_client.js:310:9)  
      at emitErrorNT (net.js:1278:8)  
      at _combinedTickCallback (internal/process/next_tick.js:74:11)  
      at process._tickCallback (internal/process/next_tick.js:98:9)  
    
  2) #superagent http://react.apptravel.cn/:  
      Uncaught TypeError: Cannot read property 'statusCode' of undefined  
      at test\test_superagent.js:20:38  
      at Request.callback (node_modules\superagent\lib\node\index.js:687:3)  
      at ClientRequest.<anonymous> (node_modules\superagent\lib\node\index.js:615:10)  
      at Socket.socketErrorListener (_http_client.js:310:9)  
      at emitErrorNT (net.js:1278:8)  
      at _combinedTickCallback (internal/process/next_tick.js:74:11)  
      at process._tickCallback (internal/process/next_tick.js:98:9)  
    
  3) #superagent http://react.apptravel.cn/article/20:  
      Uncaught TypeError: Cannot read property 'statusCode' of undefined  
      at test\test_superagent.js:20:38  
      at Request.callback (node_modules\superagent\lib\node\index.js:687:3)  
      at ClientRequest.<anonymous> (node_modules\superagent\lib\node\index.js:615:10)  
      at Socket.socketErrorListener (_http_client.js:310:9)  
      at emitErrorNT (net.js:1278:8)  
      at _combinedTickCallback (internal/process/next_tick.js:74:11)  
      at process._tickCallback (internal/process/next_tick.js:98:9)  
    
  4) #superagent https://www.baidu.com/:  
      Uncaught TypeError: Cannot read property 'statusCode' of undefined  
      at test\test_superagent.js:20:38  
      at Request.callback (node_modules\superagent\lib\node\index.js:687:3)  
      at ClientRequest.<anonymous> (node_modules\superagent\lib\node\index.js:615:10)  
      at Socket.socketErrorListener (_http_client.js:310:9)  
      at emitErrorNT (net.js:1278:8)  
      at _combinedTickCallback (internal/process/next_tick.js:74:11)  
      at process._tickCallback (internal/process/next_tick.js:98:9)  
    
  5) #superagent http://www.126.com/:  
      Uncaught TypeError: Cannot read property 'statusCode' of undefined  
      at test\test_superagent.js:20:38  
      at Request.callback (node_modules\superagent\lib\node\index.js:687:3)  
      at ClientRequest.<anonymous> (node_modules\superagent\lib\node\index.js:615:10)  
      at Socket.socketErrorListener (_http_client.js:310:9)  
      at emitErrorNT (net.js:1278:8)  
      at _combinedTickCallback (internal/process/next_tick.js:74:11)  
      at process._tickCallback (internal/process/next_tick.js:98:9)  
    
  6) #superagent https://segmentfault.com/a/1190000002748032:  
      Uncaught TypeError: Cannot read property 'statusCode' of undefined  
      at test\test_superagent.js:20:38  
      at Request.callback (node_modules\superagent\lib\node\index.js:687:3)  
      at ClientRequest.<anonymous> (node_modules\superagent\lib\node\index.js:615:10)  
      at Socket.socketErrorListener (_http_client.js:310:9)  
      at emitErrorNT (net.js:1278:8)  
      at _combinedTickCallback (internal/process/next_tick.js:74:11)  
      at process._tickCallback (internal/process/next_tick.js:98:9)
