# K6 Stat

```shell
k6-stat.js ./sample1.json ./sample2.json
```
```shell
data_received..................: 0 B   -226.2006666481302 B/s
data_sent......................: 0 B   -5.956195321009943 B/s
http_req_blocked...............: avg=27.69ms   min=27.69ms   med=27.69ms   max=27.69ms   p(90)=27.69ms   p(95)=27.69ms  
http_req_connecting............: avg=6.09ms    min=6.09ms    med=6.09ms    max=6.09ms    p(90)=6.09ms    p(95)=6.09ms   
http_req_duration..............: avg=5.9ms     min=5.9ms     med=5.9ms     max=5.9ms     p(90)=5.9ms     p(95)=5.9ms    
  { expected_response:true }...: avg=5.9ms     min=5.9ms     med=5.9ms     max=5.9ms     p(90)=5.9ms     p(95)=5.9ms    
http_req_failed................: 0.00% ✓ 0                    ✗ 0  
http_req_receiving.............: avg=-177000ns min=-177000ns med=-177000ns max=-177000ns p(90)=-177000ns p(95)=-177000ns
http_req_sending...............: avg=22.99µs   min=22.99µs   med=22.99µs   max=22.99µs   p(90)=22.99µs   p(95)=22.99µs  
http_req_tls_handshaking.......: avg=12.03ms   min=12.03ms   med=12.03ms   max=12.03ms   p(90)=12.03ms   p(95)=12.03ms  
http_req_waiting...............: avg=6.05ms    min=6.05ms    med=6.05ms    max=6.05ms    p(90)=6.05ms    p(95)=6.05ms   
http_reqs......................: 0     -0.013476/s
iteration_duration.............: avg=33.94ms   min=33.94ms   med=33.94ms   max=33.94ms   p(90)=33.94ms   p(95)=33.94ms  
iterations.....................: 0     -0.013476/s
vus............................: 0     min=0                  max=0
vus_max........................: 0     min=0                  max=0
```