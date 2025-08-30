Looking at app.py, we can see that visiting instance/developer sets a cookie if not set already and gives the flag if entered with the right cookie.

So we visit once to set the cookie, then we visit instance/static/uploads/secrets/secret_cookie.txt to find the cookie.

We set the cookie from our browsers developer settings and visit instance/developer again.



flag: scriptCTF{my_c00k135_4r3_n0t_s4f3!}
