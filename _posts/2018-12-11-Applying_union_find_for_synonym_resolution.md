---
layout: post
title: Applying union find for synonym resolution
description: Applying union find for synonym resolution
tags: [projects]
---
Recently, I have been working on a project that involves mining product reviews and generating the principal factors which customers are looking for in the product. 
 
I faced a situation where I had lot of synonyms coming up that needed to be replaced by one representative word.
Eg - [hot, burning, flaming, cat] -> [hot, hot, hot, cat] 
 
I modelled this as a problem of individually indentifying the trees in a forest and used the Union Find algorithm along with wordnet synsets to solve it. 
 
While I can't open source the entire review mining code, the Synonym Resolver can be found <a href = "https://github.com/namajain/synonymResolver">here</a>









