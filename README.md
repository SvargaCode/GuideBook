# Avatar接口使用说明

> 请求Avatar  
    - 地址：https://heroapi.juhuixinkj.com/api/Metaverse/getSpineConfig  
    - 参数：  
        * name NFT类别名称  
        * id 需要使用的NFTid  
    - 方式：post  
    - 成功返回值：  
    ```
    {
        "info": {
            "atlas": "https://bayc2.oss-cn-shenzhen.aliyuncs.com/skins/BAYC.atlas",
            "json": "https://bayc2.oss-cn-shenzhen.aliyuncs.com/skins/BAYC.json",
            "texture": "https://bayc2.oss-cn-shenzhen.aliyuncs.com/skins/BAYC2.png",
            "image": "https://bayc2.oss-cn-shenzhen.aliyuncs.com/pfp/BAYC2.png"
        },
        "status": 1
        }
    ```   
    - 说明：info下的atlas, json, texture 文件共同组成客户的需要的spine对象，image为展示用大图
