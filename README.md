# ParseModelBenchmark

对于简单数据的解析，在swift中使用 Decodable， SwiftyJSON，ObjectMapper，YYModel进行简单对比。

JSON数据
```json
{
    "id": 6,
    "position": 99,
    "price": 3,
    "own": true,
    "name": "小兔子",
    "provider": "私人提供",
    "accessoryName": "头饰6",
}
```
测试量为5w次。

电脑配置：
MacBook Pro (Retina, 15-inch, Mid 2015)
处理器 2.2 GHz 四核Intel Core i7
内存 16G
xcode： 11.1
模拟器：iPhone 11 pro max

Decodable: 0.90-0.94(sturct 与 class 区别不大)

SwiftyJSON: 1.31-1.40

ObjectMapper: 0.58-0.61

YYModel: 0.32-0.35

