# ObjectC_History

Object C 是 Mac OS 的一種開發語言，簡稱為 object 或是 Obj-C。誕生於 1980 年代，但到 1996 年方才成為蘋果的程式語言。

在 2004 年，所有的 * Nix 作業系統其 class 和 method 均以 NS 為字守，表示此工具來自 Cocoa 而非其他工具。 (此命名源自於 NeXTStep)

特色


                   string
                   class
            C   +  method   =   Object-C
                   property
                   protocol
                   group(inheritance)

結構


                     obj-C
                     
                       |
             _______________________
            |          |           |
            
          build       obj-c     obj-c.xcodeproj        
            |       ____｜____           
                   |    |    |
          obj-c-Prefix.pch  main.m
                        |
                      obj-c.l
 
main 方法

             #import <Foundation/Foundation.h>    -----> 標頭檔案
             
             
             int main(int argc, const char * argv[])
             {
                NSLog(); -------> 執行區塊
                treturn 0;
             }
