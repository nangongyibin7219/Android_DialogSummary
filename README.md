# 
对话框样式


## How to ##

To get a Git project into your build:

### Step 1. Add the JitPack repository to your build file ###

Add it in your root build.gradle at the end of repositories:

    allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

### Step 2. Add the dependency ###

    dependencies {
	        implementation 'com.github.nangongyibin:Android_DialogSummary:1.0.5'
	}

### CustomerDialog示例图 ###

![](https://github.com/nangongyibin/Android_DialogSummary/blob/master/example-customer.png?raw=true)

### selfDialog示例图 ###

![](https://github.com/nangongyibin/Android_DialogSummary/blob/master/example-self.png?raw=true)