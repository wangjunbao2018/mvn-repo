# mvn-repo
Make git as a maven repo.

# Make git as mvn repo

```
cd ~/.m2/repository/
git init
git remote add origin https://github.com/wangjunbao2018/mvn-repo.git
git add  one
git commit -a -m 'first commit'
git push -u origin master
```

# Add the dependency

## Add repository

```
repositories {
    maven {
        url 'https://raw.github.com/wangjunbao2018/maven-repo/master/0.0.1'
    }
}

```

## Add dependency

```
compile 'one.contentbox.boxd:boxd-client:0.0.1'
```


