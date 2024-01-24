<% set "Operation" (capitalize (get "operation")) %>
<% set "FileFormat" (get "fileformat") %>
<% set "FileFormatUp" (upper (get "fileformat")) %>
<% set "FileformatCap" (capitalize (get "fileformat")) %>
<% set "ProductName" (dict "products.{product}.name") %>
<% set "ProductFullName" (dict "products.{product}.fullName") %>
<% set "ProductCode" (dict "products.{product}.code") %>
<% set "ProductUrl" (dict "products.{product}.url") %>
<% set "ProgLang" (dict "products.{product}.progLang") %>
<% set "SrcFileExt" (dict "products.{product}.srcFileExt") %>
<% set "DevEnv" (dict "products.{product}.devEnv") %>
<% set "Runtime" (dict "products.{product}.runtime") %>
<% set "RepoName" (dict "products.{product}.repoName") %>
<% set "RepoUrl" (dict "products.{product}.repoUrl") %>
<% set "MoreLink" (dict "products.{product}.more_link") %>
<% set "ReleaseDownloads" (dict "products.{product}.release_downloads") %>
<% set "DocsLink" (dict "products.{product}.docs_link") %>
<% set "PricesLink" (dict "products.{product}.prices_link") %>
