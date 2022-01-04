# ipdb-java
用于解析IPDB格式离线数据库

# 代码示例
<pre>
        try {
            BaseStation db = new BaseStation("res/ipv6.ipdb");
            System.out.println(db.buildTime());
            System.out.println(db.languages());
            System.out.println(db.fields());
            System.out.println(db.isIPv6());
            System.out.println(db.findInfo("240e:398:1:90a0:585e:a0f6:97d3:bd5","CN"));
        } catch (Exception e) {
            e.printStackTrace();
        }
</pre>

