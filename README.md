# Nginx Patches by MDounin 

## Background

This is a repository that I mantain with patches provided by by [Maxim Dounin](http://mdounin.ru)
for Nginx. Most of these patches where provided in a
[thread](http://mailman.nginx.org/pipermail/nginx-devel/2011-September/001150.html)
of the [nginx-devel](http://nginx.org/mailman/listinfo/nginx-devel)
mailing list.

It includes also other patches posted to the
[nginx-devel](http://nginx.org/mailman/listinfo/nginx-devel) mailing list.

## Upstream Keep-Alive

Part of
[upstream keep-alive](http://mailman.nginx.org/pipermail/nginx-devel/2011-September/001129.html)
patches are included. Some parts seem to be already included in the
development version. Also the `ngx_http_upstream_keepalive_module` is
not included. You must download it separately from
[Maxim Dounin's repo](http://mdounin.ru/hg/ngx_http_upstream_keepalive/).

## Application

I applied the **non-rejected** patches to build my
[nginx deb](http://debian.perusio.net "My Debian Repo with up to date
Nginx") package of the **1.1.2** version with the
`upstream-keep-alive` patch and module.

If any of the patches don't apply cleanly, they're moved to the `rejected`
directory.

This repository is provided as a **convenience** since as of now there's
no _official_ repo of theses patches. They're being provided **solely**
through the mailing list.
