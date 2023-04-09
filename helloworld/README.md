# How to display alert dialog in android.

You could use an AlertDialog for this and construct one using its Builder class. The example below uses the default constructor that only takes in a Context since the dialog will inherit the proper theme from the Context you pass in, but there's also a constructor that allows you to specify a specific theme resource as the second parameter if you desire to do so.
