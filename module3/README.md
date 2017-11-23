How to use login.jar?

Add this jar to your projects build path.

=========================================================================


import com.fm.login.Authentication;

==========================================================================





Authentication a = new Authentication();

boolean result = a.login("someusername", "9841001144")


System.out.println(result);



=========================================================================
The login method should return "true" for a sucessful login.
