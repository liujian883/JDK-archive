<h1><img alt="" src="icon_jdk.png"/> JDK Archive</h1>

 - JDK <code>6</code>/<code>7</code><code>8</code><code>9</code> for Windows (x86/x64) - Flatten Setup.
 - <code>8</code>/<code>9</code> Docs <strong>(IF YOU HAVE <code>6</code>/<code>7</code> <em>"-docs-all.zip"</em> FILE --- PLEASE CONTACT ME!!!)</strong>
 - <code>6</code>/<code>7</code><code>8</code> JCE-Policy (original signed-JAR files).

 - All JDK setups/docs/policy are extracted as much as possible and compressed with 7Zip.
 - <img alt="" src="icon_setup.png"/> Flatten setup, is stripping few layers of extraction (exe to MSI-archive to MSI-folder),
   it makes running the setup easier/faster, allows embedding it/slipstream it into other setups,
   and makes 7zip compress (for this archive) more-efficient.

<hr/>

Some tips:

Here are few environment-variables you
need to set, since you are using Windows,
Press [WIN]+[PAUSE], and get into advanced-system-properties.
<sub><em>on Win7, you can run: <code>C:\Windows\system32\systempropertiesadvanced.exe</code></em></sub>

<pre>
JAVA_HOME   C:\PROGRA~1\Java\JDK17~1.0_8
JRE_HOME    C:\PROGRA~1\Java\JDK17~1.0_8\jre
PATH        ......C:\PROGRA~1\Java\JDK17~1.0_8\bin;....
</pre>

Keep in-mind to use short-path format (a.k.a 8.3 old DOS format),
it really helps with many bugs (especially in JDK 6/7),
and add the short-path with "\bin" prefix to your environment-PATH.

You need to restart your PC, and then type: <code>where java.exe</code>,
and to get something like: <code>C:\Program Files\Java\jdk1.7.0_80\bin\java.exe</code>.
You can also type <code>java.exe -version</code>, and to get something like:
<pre>
java version "1.7.0_80"
Java(TM) SE Runtime Environment (build 1.7.0_80-b15)
Java HotSpot(TM).....
</pre>

<sub><em>Gosh.. it took a lot of work... ***cough*** ***ahhmmm...***</em></sub>
<sub><a target="_blank" href="https://paypal.me/e1adkarak0" rel="nofollow"><img src="https://www.paypalobjects.com/webstatic/mktg/Logo/pp-logo-100px.png" width="60" height="16" border="0" alt="PayPal Donation"></a></sub>
