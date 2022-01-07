---
title: Introduction
subtitle: A library to rule them all, a library to find them. A library to bring them all, and in the shelves bind them. 
description: ''
position: 1
category: 'Getting started'
features:
  - Feature 1
  - Feature 2
  - Feature 3
---

<img src="/preview.png" class="light-img" width="1280" height="640" alt=""/>
<img src="/preview-dark.png" class="dark-img" width="1280" height="640" alt=""/>

Bookshelves offers to create a web application with an documented API **to present your eBooks** (EPUB) **and your comics** (CBZ). You can check a **Bookshelves demo** at [bookshelves.ink](https://bookshelves.ink).

<alert type="warning">

Currently in beta.

</alert>

## Features

<list :items="features"></list>

<p class="flex items-center">Enjoy light and dark mode:&nbsp;<app-color-switcher class="inline-flex ml-2"></app-color-switcher></p>

## Links

🚀 [**bookshelves.ink**](https://bookshelves.ink): demo of Bookshelves  

### *Features*

🔒 [**bookshelves.ink/admin**](https://bookshelves.ink/admin): admin of Bookshelves usage  
📔 [**bookshelves.ink/wiki**](https://bookshelves.ink/wiki): wiki for Bookshelves usage  
👩‍💻 [**bookshelves.ink/docs**](https://bookshelves.ink/docs): API documentation  
🔖 [**bookshelves.ink/opds**](https://bookshelves.ink/opds): OPDS feed for applications which can read this feed  
📚 [**bookshelves.ink/catalog**](https://bookshelves.ink/catalog): Catalog, a basic interface for eReader browser to download eBook from eReader  
📖 [**bookshelves.ink/webreader**](https://bookshelves.ink/webreader): Webreader, to read any Bookshelves eBook into your browser  

### *Repository*

📀 [**gitlab.com/bookshelves-project/bookshelves-back**](https://gitlab.com/bookshelves-project/bookshelves-back) : back-end of Bookshelves  
🎨 [**gitlab.com/bookshelves-project/bookshelves-back**](https://gitlab.com/bookshelves-project/bookshelves-back) : front-end of Bookshelves  

### *What Bookshelves is not*

Bookshelves is not like Calibre with dynamic database from EPUB into a specific directory, with Bookshelves you have to parse all EPUB in a directory and, if you add another, you have to parse for new EPUB (fastly than first parse) to generate new eBooks for database. You can use this application like Calibre but it's not same. If you want a Calibre app for web, check these projects:

- [**github.com/janeczku/calibre-web**](https://github.com/janeczku/calibre-web)
- [**github.com/seblucas/cops**](https://github.com/seblucas/cops)
