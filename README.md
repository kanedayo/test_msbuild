* https://kyabatalian.hatenablog.com/entry/2019/01/06/170759
* https://docs.microsoft.com/ja-jp/visualstudio/msbuild/walkthrough-creating-an-msbuild-project-file-from-scratch
* https://codezine.jp/article/detail/674

```bash
PATH=/cygdrive/c/Program\ Files\ \(x86\)/MSBuild/14.0/Bin/:$PATH
#PATH=/cygdrive/c/Windows/Microsoft.NET/Framework/v2.0.50727:$PATH

msbuild Helloworld.proj -t:Build
msbuild Helloworld4.proj -t:Rebuild
```


```cmd
:set PATH="C:\Program Files (x86)\MSBuild\14.0\Bin";%PATH%
set PATH=C:\WINDOWS\Microsoft.NET\Framework\v2.0.50727;%PATH%

msbuild Helloworld.proj -t:Build
```
