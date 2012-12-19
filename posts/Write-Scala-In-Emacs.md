---
title: Write Scala In Emacs
date: '2012-12-19'
description:
categories: 
   - programming
   - scala
---

# Install scala 

Follow the [link](http://jawher.net/2011/01/17/scala-development-environment-emacs-sbt-ensime/).

# Install sbt
1. download [laucher](http://repo.typesafe.com/typesafe/ivy-releases/org.scala-sbt/sbt-launch//0.12.1/sbt-launch.jar) file
2. Create a file named sbt, and copy the following script to it.
        
		java -Xms512M -Xmx1536M -Xss1M -XX:+CMSClassUnloadingEnabled -XX:MaxPermSize=384M -jar `dirname $0`/sbt-launch.jar "$@"

3. save sbt file and make it excutable

        chmod +x sbt
		
4. add the path of sbt to $PATH.(modify .bashrc)

# Install Ensime
1. Install [scale-mode](https://github.com/haxney/scala-mode)
2. Install [Ensime](http://aemoncannon.github.com/ensime/index.html#tth_sEc2)
3. add the following in your .sbt/plugins/plugins.sbt (if this file doesn't exist, create one)
    
	     addSbtPlugin("org.ensime" % "ensime-sbt-cmd" % "version")
	 
where version is the sbt version. (e.g., "0.1.0")

# Create simple Project
Follow [here](https://github.com/softprops/np)



