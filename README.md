# java_plateNumber_verifier
> Nigerian Vehicle Plate Number Verifier (JAVA)

This library enables you verify plate number (of Nigerian vehicles) ang get the details
of the vehicle and the verified owner.

## Installation

To use, simply download the included zip file and copy the contained jar files to your working directory.


## Example usage:
```java
import verifier.VerifiedOwner;

import verifier.VerifyOwner;

VerifyOwner vo = new VerifyOwner("FST918EH");

VerifiedOwner vv = vo.verify();

java.util.Date issue_date = vv.get_issue_date();
```

Available details:
After getting an instance of VerifiedOwner (which is what VerifyOwner({number}).verify()) would return, you can do these:

```java
//assuming the object is called 'vv'

String owner = vv.get_owner();

String model = vv.get_model();

String colour = vv.get_colour();

String chasis_number = vv.get_chasis_number();

java.util.Date issue_date = vv.get_issue_date();

java.util.Date expiry_date = vv.get_expiry_date();
  
```


This library is licensed under the <a href="https://github.com/yusufoguntola/JavaNumberVerifier/blob/master/LICENSE.txt">MIT License.</a> Please take a look at it!


Enjoy!!!
