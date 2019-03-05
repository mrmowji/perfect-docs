# Perfect Documentation
It's not about documentation inside your code.
It's about online documentation related to a technology (HTML, CSS, JS, .NET, etc) presented to the end user.

## Suggestions
Please consider the following statements:
* Think about users first, not search engines. It might not be obvious. Let's examine MDN website. It's one of the bests, but it could simply be better. One of the big problems I experienced in almost all MDN pages, was the number of links inside the main content. Almost
all keywords are linked to their corresponding page. You might say that's not a problem. It might sound good from user or SEO
perspective. But the user (reader) shouldn't follow all those links and then come back to your article to understand what you've written; that's just spaghetti. User must be notified of all prerequisities of that content/article before she/he dives in. That way all links are at the top, and the content is clutter-free. That's the perfect experience I could imagine for myself. Putting links just for the sake of SEO isn't a good thing here.
* Direct user with a tree-like navigation. This is actually a part of the previous statement. What does "tree-like" mean? Let's start with the definition of nodes here. A node in this context, is simply a set of pages that are related in some way and should be learned at once; a node can have 1 or more pages in it. Now about the tree itself. Your documentation about a technology must have a single entry page for users who want to learn from scratch (it's the root node or level 0). Then you should navigate the user to another node in the next-level that user could understand with what she/he has already learned (these nodes compose level 1 of the tree). Instead of navigating you can show all next-level nodes and let the user choose.
* If you have a navigation menu for topics of your technology, show links to all those page to the user, even if they're on the side of the main content. You can use SPA to load only the main content and prevent loading all those navigation menu links each time the user visits the page. Don't use "more" or pagination. Let the user know how much information she/he needs to know about the technology.
* It's a good thing to apply Pareto principle to your nodes/pages. Divide your nodes/pages while specifying which ones could be in the 20% that would be enough in 80% of situations. Keep previous statemtnets in mind. This way the user would know how much she/he must learn to be confident in other situations. For example, if you're documenting HTML, the `<kbd>` element could be categoried in the remaining 80%, but `<p>` is kind of neccessory in all situations and should be in the first 20% category.
