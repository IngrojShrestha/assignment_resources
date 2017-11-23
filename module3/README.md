How to use login.jar?

Add this jar to your projects build path.

=========================================================================


import com.fm.login.Authentication;

==========================================================================





Authentication a = new Authentication();

boolean result = a.login("someusername", "somepassword");


System.out.println(result);
