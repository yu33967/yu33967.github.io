# Github+PIGGO+Typro 实现图床

## 1. 在GITHUB 创建 图床仓库

![GITHUB 创建图床仓库](https://raw.githubusercontent.com/yu33967/pics/main/images/202411241813475.png)

## 2. 创建TOKEN

![GITHUB 创建图床Token](https://raw.githubusercontent.com/yu33967/pics/main/images/202411241813840.png)

![GITHUB 创建图床Token-2](https://raw.githubusercontent.com/yu33967/pics/main/images/202411241813460.png)

![GITHUB 创建图床Token-3](https://raw.githubusercontent.com/yu33967/pics/main/images/202411241814185.png)

![GITHUB 创建图床Token-4](https://raw.githubusercontent.com/yu33967/pics/main/images/202411241814688.png)

## 3. 安装PIGGO

![PIGGO设置](https://raw.githubusercontent.com/yu33967/pics/main/images/202411241814007.png)

## 4. 设置PIGGO

![PIGGO设置-2](https://raw.githubusercontent.com/yu33967/pics/main/images/202411241814075.png)

## 5. PIGGO上传失败（原因及解决方案）

### 5.1 上传失败

>unable to verify the first certificate
>
>解决方案：关闭加速软件（当时有使用stream++加速）

### 5.2 PIGGO上传成功，PIGGO图册及Typro不显示图片

>Piggo 图册显示为空
>
>解决方案：修改hosts文件的自己使用的图片域名 例如raw.githubusercontent.com
>
>在网站https://www.ipaddress.com 或 sitereport.netcraft.com 解析域名 修改域名

 #### 5.2.1 打开host文件 （c:\windows\system32\drivers\etc\hosts）末尾增加以下内容

```tex
# GitHub Start 
140.82.113.3      github.com
140.82.114.20     gist.github.com
 
151.101.184.133    assets-cdn.github.com
151.101.184.133    raw.githubusercontent.com
151.101.184.133    gist.githubusercontent.com
151.101.184.133    cloud.githubusercontent.com
151.101.184.133    camo.githubusercontent.com
151.101.184.133    avatars0.githubusercontent.com
199.232.68.133     avatars0.githubusercontent.com
199.232.28.133     avatars1.githubusercontent.com
151.101.184.133    avatars1.githubusercontent.com
151.101.184.133    avatars2.githubusercontent.com
199.232.28.133     avatars2.githubusercontent.com
151.101.184.133    avatars3.githubusercontent.com
199.232.68.133     avatars3.githubusercontent.com
151.101.184.133    avatars4.githubusercontent.com
199.232.68.133     avatars4.githubusercontent.com
151.101.184.133    avatars5.githubusercontent.com
199.232.68.133     avatars5.githubusercontent.com
151.101.184.133    avatars6.githubusercontent.com
199.232.68.133     avatars6.githubusercontent.com
151.101.184.133    avatars7.githubusercontent.com
199.232.68.133     avatars7.githubusercontent.com
151.101.184.133    avatars8.githubusercontent.com
199.232.68.133     avatars8.githubusercontent.com
 
# GitHub End

```

#### 5.2.2 上述如果无法解决 ，找到自己的域名 ，查询对应在IP，修改hosts对应域名在IP.

#### 5.2.3 刷新DNS解析缓存。cmd ->执行 ipconfig/flushdns

![刷新DNS解析缓存](https://raw.githubusercontent.com/yu33967/pics/main/images/202411241814488.png)

## 6. Typro通过PIGGO上传GITHUB图。

#### 6.1 文件-偏向设置

![Typora设置](https://raw.githubusercontent.com/yu33967/pics/main/images/202411241814322.png)

### 6.2 导入图片 上的 '上传图片'

![Typora设置-上传图片](https://raw.githubusercontent.com/yu33967/pics/main/images/202411241815182.png)