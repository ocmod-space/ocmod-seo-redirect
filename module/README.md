# SEO Redirect

## Description
**SEO Redirect** is an OpenCart extension that allows to redirect requests to outdated URLs to new URLs using HTTP 301 response status code. This way, search engines will be notified that the requested resource has finally moved to a new URL, and they will update their links to the resource. Also allows to log broken (404) requests and redirect them to the search page.  
Compatible with OpenCart 3x versions.

## Features
* Redirection from old URLs to corresponding new URLs with an HTTP 301 status code.
* Smart update aliases when the store admin change SEO URLs, thus requests to the old URLs will always be redirected to the new ones.
* Log broken requests that lead to 404 page.
* Redirecting the 404 pages to the search page with the first keyword or a tag (search, tag, description), if it exists.
* Does not modify system files (OCMOD).

## Live demo
* Extension [settings](https://demo.ocmod.space/a/admin/index.php?route=extension/module/seo_redirect).
* [Store Front](https://demo.ocmod.space/a).

## License
[End-user License Agreement](https://raw.githubusercontent.com/ocmod-space/ocmod-seo-redirect/main/EULA.txt).

## Links
* **SEO Redirect** on [**OpenCart Marketplace**](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=45459).
* [**SEO Redirect**](https://www.ocmod.space/seo-redirect) web page.

## Related extensions
* [**SEO Path**](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=38192) - is a simple but powerful extension that allows to control store URLs and breadcrumb trails, implement static pagination, uses smart redirection, improve important aspects of multilingual stores and other things to make store more SEO-friendly.
* [**SEO Common Urls**](https://github.com/ocmod-space/ocmod-seo-common-urls) - is an extension that assigns SEO keywords for the common URLs and removes.
