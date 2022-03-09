# bilibili主页面

## content_top 
这一行肯定是flex布局，但是问题是，当页面变大变小时，他的这个left,middle,right会改变，那么显然不是flex布局当中的比例，由于当前不会媒体查询，所以先写一下125%下的页面

### content_top_left    
flex布局，每一个都是三等分，很简单

### content_top_middle
grid布局

### content_top_right
gird布局


## content_layout
主页面下面的轮播图和视频集

### content_layout banner
轮播图，有2种方式实现
第一种：js直接写好，后台取图片放入写好的位置
第二种，dom操作元素直接链接视频地址

### content_layout video_card