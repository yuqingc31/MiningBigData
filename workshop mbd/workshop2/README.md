关于本次的workshop，我在安装fancyimpute的时候遇到了点小问题。
我的报错：   3abs44ag/overlay/lib/python3.9/site-packages/numpy/core/include -I/Applications/Xcode.app/Contents/Developer/Library/Frameworks/Python3.framework/Versions/3.9/Headers -I/Library/Python/3.9/include -fvisibility=hidden -fdiagnostics-color=always -DNDEBUG -Wall -Winvalid-pch -O3 -F/Library/Developer/CommandLineTools/SDKs/MacOSX.sdk/System/Library/Frameworks/Accelerate.framework -idirafter/Library/Developer/CommandLineTools/SDKs/MacOSX.sdk/System/Library/Frameworks/Accelerate.framework/Headers -Wno-unused-result -DPYTHON -DCTRLC=1 -DUSE_LAPACK=1 -DDLONG=1 -MD -MQ _scs_direct.cpython-39-darwin.so.p/scs_scspy.c.o -MF _scs_direct.cpython-39-darwin.so.p/scs_scspy.c.o.d -o _scs_direct.cpython-39-darwin.so.p/scs_scspy.c.o -c ../scs/scspy.c
      ../scs/scspy.c:15:10: fatal error: 'Python.h' file not found
我的设备： MacOS
python版本：python3

如果你也遇到了这个报错，请检查你的设备是否有Xcode，如果没有Xcode就要去app store下载。下载完Xcode就重新安装fancyimpute