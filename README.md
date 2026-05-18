1) 1. Within a Github action that runs whenever code is pushed. This would allow devs to not even have to think about running tests. It would happen automatically when code is pushed which ensures no bad code is kept on the remote repo. This provides continuous, automatic, and enforceable quality control across the team.
2) No
3) Navigation will analyze the page from a full reload, measuring its performance after loading from scratch while snapshot mode will analyze the page as it currently exists.  
4) Three things to do to improve the website based on lighthouse results:
   1) Performance: Avoid chaining critical requests. Can be done by reducing the length of chains, reducing the dowload size of resources, or deferring the download of unnecessary resources to improve page load.
   2) Accessibility: The ``<html>`` element does not have ``[lang]`` attribute. This can cause screen readers to not announce the page's text correctly beacuse it will choose the default language of the screen reader rather than the language of the page
   3) SEO: The document does not have meta description which hinders its accessibility from search engines