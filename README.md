I moved this project from GoogleCode because Google Code is not graceful for ME.

And, I've changed this project to a Maven structure. If you're using maven as your
primary project management tool, from now on, your can just easily put this
block into your `pom.xml`, enjoy it!


```
<repositories>
    <repository>
        <id>kaptcha-mvn-repo</id>
        <url>https://raw.github.com/bilxio/kaptcha/mvn-repo/</url>
        <snapshots>
            <enabled>true</enabled>
            <updatePolicy>always</updatePolicy>
        </snapshots>
    </repository>
</repositories>
```

BTW: about how to use maven in Github, many thanks to this article:
http://stackoverflow.com/questions/14013644/hosting-a-maven-repository-on-github


Here's the original content of README:

> kaptcha - A kaptcha generation engine.
> Please see the website for more information about this project.
> http://code.google.com/p/kaptcha/
> thanks!
