# Laravel Lumen Mailchimp integration

This project is based on a really simple version of [Laravel Lumen][1].

## Context

The API is built to interact with [MailChimp via their API][2], handling CRUD operations for [LISTS][3] and [MEMBERS][4].

This project assumes all interaction will take place via this API, therefore data should be stored locally and
only retrieved from MailChimp when required.

## Requirements

This task requirements are as follows:

- Each external libraries are loaded via [composer][5]
- The database layer used is [Doctrine][6] via the [laravel-doctrine/orm][7] package
- The interaction with [MailChimp API][3] is made using [pacely/mailchimp-apiv3][8]
- [Register on MailChimp][9], create your API key to use in your application
- [Postman][10] to test your API

[1]: https://lumen.laravel.com
[2]: http://developer.mailchimp.com/documentation/mailchimp/reference/overview
[3]: http://developer.mailchimp.com/documentation/mailchimp/reference/lists
[4]: http://developer.mailchimp.com/documentation/mailchimp/reference/lists/members
[5]: https://getcomposer.org/
[6]: http://www.doctrine-project.org/projects/orm.html
[7]: https://www.laraveldoctrine.org/docs/1.3/orm
[8]: https://github.com/pacely/mailchimp-api-v3
[9]: https://login.mailchimp.com/signup/
[10]: https://www.getpostman.com/
