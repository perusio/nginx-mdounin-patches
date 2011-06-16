# Nginx Patches by MDounin 

## Background

This is the patch queue provided by [Maxim Dounin](http://mdounin.ru)
for Nginx. These patches where provided in a
[thread](http://nginx.org/pipermail/nginx-devel/2011-February/000719.html)
of the [nginx-devel](http://nginx.org/mailman/listinfo/nginx-devel)
mailing list.

There is also a later patch for a
[FastCGI duplicated request header](http://nginx.org/pipermail/nginx-devel/2011-June/000943.html)
issue that originated a core dump.

## Application

I applied the **non-rejected** patches to build my
[nginx deb](http://debian.perusio.net "My Debian Repo with up to date
Nginx") package of the **1.0.4** version.

Some of the patches didn't apply cleanly. They're in the `rejected`
directory.

This repository is provided as a **convenience** since as of now there's
no _official_ repo of theses patches. They're being provided **solely**
through the mailing list.
