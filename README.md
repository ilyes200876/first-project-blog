* composer create-project symfony/website-skeleton blog "5.4.*”
* symfony local:php:list
* symfony console doctrine:database:create
* composer require annotations
* symfony console make:User
* symfony console make:entity User
* * * firstName (string)
* * * lastName (string)
* * * email (string)
* symfony console make:entity
*  * Article
* * * title (string)
* * * content (text)
* symfony console make:entity
* * Comment
* * * content (text)
* symfony console make:entity User
* * * articles
* * * relation
* * * Article
* * * OneToMany
* * * comments
* * * relation
* * * Comment
* * * OneToMany
* symfony console make:entity Article
* * * comments
* * * relation
* * * Comment
* * * OneToMany


