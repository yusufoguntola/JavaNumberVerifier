Nigerian Vehicle Plate Number Verifier (JAVA)

This library enables you verify plate number (of Nigerian vehicles) and get the details
of the vehicle and the verified owner.

To use, simply download the included zip file and copy the contained jar files to your working directory.

Example usage:
<code>import verifier.VerifiedOwner;</code>

<code>import verifier.VerifyOwner;</code>

<code>VerifyOwner vo = new VerifyOwner("FST918EH");</code>

<code>VerifiedOwner vv = vo.verify();</code>

<code>java.util.Date issue_date = vv.get_issue_date()</code>

Available details:
After getting an instance of VerifiedOwner (which is what VerifyOwner({number}).verify()) would return, you can do these:

<code>//assuming the object is called 'vv'</code>

<code>String owner = vv.get_owner()</code>
  
<code>String model = vv.get_model()</code>
  
<code>String colour = vv.get_colour()</code>
  
<code>String chasis_number = vv.get_chasis_number()</code>
  
<code>java.util.Date issue_date = vv.get_issue_date()</code>
  
<code>java.util.Date expiry_date = vv.get_expiry_date()</code>
  



This library is licensed under the <a href="https://github.com/yusufoguntola/JavaNumberVerifier/blob/master/LICENSE.txt">MIT License.</a> Please take a look at it!


Enjoy!!!
