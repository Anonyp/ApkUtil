# ApkUtil

#利用aapt获取App内部信息

```java
try {
            String apkpath = "文件地址";
            if (args.length > 0) {
                apkpath = args[0];
            }
            ApkInfo apkInfo = new ApkUtil().getApkInfo(apkpath);
            // 打印获取到的信息
            System.out.println(apkInfo);
            
        } catch (Exception e) {
            e.printStackTrace();
        }