# README

So I've got this super weird bug:

in `app/views/shared/navbar.html.erb`, uncomment the third li tag (line 7).

See how it breaks the h1 directly below ? I tried to fix it with the clearfix hack and it works...

except that it messes up the layout with my navbar in the About and Contact pages. Bummer.

