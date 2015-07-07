# Awesome Symfony 2
A list of awesome [Symfony 2](http://rdir.io/8Cd) bundles, utilities and resources.

Table of contents:

* [User Management](#user-management)
* [Web Services](#web-services)
* [Template Engine](#template-engine)
* [Storage](#storage)
* [Validation](#validation)
* [Forms](#forms)
* [Service Container](#service-container)
* [Development](#development)
* [Assets Management](#assets-management)
* [Queues](#queues)
* [Internationalization](#internationalization)
* [Payments Management](#payments-management)
* [Monitoring](#monitoring)
* [Miscellaneous](#miscellaneous)
* [Third Party APIs](#third-party-apis)
* [Reading](#reading)
* [Distributions](#distributions)

## User Management

 * [FOSUserBundle](http://rdir.io/t02) - Adds support for a database-backed user system.
 * [HWIOAuthBundle](http://rdir.io/qMF) - OAuth client integration. Supports both OAuth1.0a and OAuth2.
 * [JmikolaAutoLoginBundle](http://rdir.io/qE5) - This bundle integrates the AutoLogin library with Symfony2, which implements a security firewall listener to authenticate users based on a single query parameter.
 * [JMSSecurityExtraBundle](http://rdir.io/eAf) - Enhances the Security Component with several new features.

## Web Services

 * [api-key-bundle](http://rdir.io/QqN) - Creates an avenue for using ApiKey authentication for Symfony2.
 * [BazingaHateoasBundle](http://rdir.io/zI2) - Integration of the Hateoas library.
 * [FOSOAuthServerBundle](http://rdir.io/SSh) - A server side OAuth2 bundle.
 * [FOSRestBundle](http://rdir.io/Uzi) - Provides various tools to rapidly develop RESTful API's & applications.
 * [HydraBundle](http://rdir.io/i2M) - A Symfony2 bundle which shows how easily Hydra can be integrated in modern Web frameworks. It acts as a proof of concept to show how Hydra can simplify the implementation of interoperable and evolvable RESTful APIs.
 * [JMSSerializerBundle](http://rdir.io/QvL) - Easily serialize, and deserialize data of any complexity.
 * [KnpJsonSchemaBundle](http://rdir.io/Bh1) - Provide a service which allow you to generate json schema based on validation metadata.
 * [LemonRestBundle](http://rdir.io/13F) - An opinionated bundle providing REST endpoints for Doctrine entities.
 * [LexikJWTAuthenticationBundle](http://rdir.io/0vj) - This bundle provides JWT (Json Web Token) authentication for your REST API using the namshi/jose library.
 * [NelmioApiDocBundle](http://rdir.io/aTm) - Generates documentation for your REST API from annotations.
 * [NelmioCorsBundle](http://rdir.io/J23) - Adds ability to add CORS-related headers based on simple ACL-style per-URL configurations.
 * [RateLimitBundle](http://rdir.io/c2g) - Add rate limits to your controllers/actions easily through annotations.
 * [RequestLimitBundle](http://rdir.io/PbZ) - With this bundle you can easy limit requests to your application.
 * [ResourceBundle](http://rdir.io/h7j) - Bundle that helps in developing REST APIs.
 * [SerializedResponseBundle](http://rdir.io/WCR) - A simple bundle to provide an easy way to send out json/xml/yaml responses of serialized objects with annotations.

## Template Engine

 * [CgKintBundle](http://rdir.io/eCe) - This bundle lets you use the Kint library in your Twig templates.
 * [GravatarBundle](http://rdir.io/apF) - Simple wrapper to gravatar API.
 * [KnpTimeBundle](http://rdir.io/VCF) - Provides helpers for time manipulation.
 * [twig-inflection](http://rdir.io/GnB) - Apply inflection.
 * [TwigCacheBundle](http://rdir.io/GvE) - Bundle for asm89/twig-cache-extension.
 * [TwigCallableBridgeBundle](http://rdir.io/pNA) - Provides a simple interface to use PHP function with Twig templates.
 * [TwigExtraBundle](http://rdir.io/0ei) - Twig Extra Tools Extensions.
 * [TwigJackBundle](http://rdir.io/0it) - Handy additional features for Twig.
 * [TwitalBundle](http://rdir.io/HO5) - An attribute template engine built on top of Twig and 100% compatible with all twig's features.
 * [UcoTwigExtensionsBundle](http://rdir.io/xUr) - Provides some filters.

## Storage

 * [AliceBundle](http://rdir.io/Q2p) A Symfony2 bundle to help load Doctrine Fixtures with Alice.
 * [AliceFixturesBundle](http://rdir.io/vpj) - A Symfony2 bundle for using Alice and Faker with data fixtures.
 * [doctrine-routing-bundle](http://rdir.io/RHe) - Dynamic database routing.
 * [DoctrineEncryptBundle](http://rdir.io/Eob) - Bundle allows you to create doctrine entities with fields that will be protected by encryption algorithms such as AES.
 * [DoctrineEnumBundle](http://rdir.io/H9L) - Provides support of MySQL ENUM type for Doctrine2.
 * [DoctrineFixturesBundle](http://rdir.io/t6T) - Integrates the Doctrine2 Data Fixtures library.
 * [DoctrineMigrationsBundle](http://rdir.io/tB5) - Integrates the Doctrine2 Migrations library.
 * [elastica-query-bundle](http://rdir.io/Fyw) - Query builder bundle for ElasticSearch.
 * [FeedBundle](http://rdir.io/RGf) - A bundle to build RSS feeds from your entities.
 * [FPNTagBundle](http://rdir.io/G8M) - This bundle adds tagging, with the ability to associate tags with any number of different entities.
 * [GaufretteBrowserBundle](http://rdir.io/SDP) - This Bundle allows you to browse a Gaufrette Filesystem like a Doctrine Connection.
 * [KnpGaufretteBundle](http://rdir.io/l6N) - Integrates Gaufrette.
 * [MysqlDoctrineFunctions](http://rdir.io/GZb) - MySQL Function for Doctrine : RAND(), ROUND() DATE(), DATE_FORMAT().
 * [OneupFlysystemBundle](http://rdir.io/GH8) - Integrates Flysystem.
 * [PasswordStrengthBundle](http://rdir.io/pOV) - Validator for ensuring strong passwords.
 * [RelationBundle](http://rdir.io/fx3) - Bundle to manage relations between models/entities. (Not maintained anymore)
 * [SncRedisBundle](http://rdir.io/2SG) - Bundle to integrate Redis into your app.
 * [StofDoctrineExtensionsBundle](http://rdir.io/n6R) - This bundle provides integration for DoctrineExtensions.
 * [VichGeographicalBundle](http://rdir.io/ygI) - A bundle which provides geographical features for ORM and ODM entities and object oriented javascript maps rendering.
 * [VichUploaderBundle](http://rdir.io/I1Y) - A simple Symfony2 bundle to ease file uploads with ORM entities and ODM documents.
 * [WizadDoctrineDocBundle](http://rdir.io/S7M) - Allows you to generate a decent documentation for your doctrine model schema.

## Validation

 * [dms-filter-bundle](http://rdir.io/UIM) - Provides a FilterService to allow users to implement input filtering in entities using Annotations.

## Forms

 * [CaptchaBundle](http://rdir.io/VDs) - Bundle implementing a "captcha" form type.
 * [CraueFormFlowBundle](http://rdir.io/R5X) - Multi-step forms.
 * [FilterFormBundle](http://rdir.io/xkC) - Filter form bundle.
 * [FormBundle](http://rdir.io/KkZ) - Provides the "entity_id" type.
 * [IbrowsXeditableBundle](http://rdir.io/nDr) - X-editable forms integration.
 * [InfiniteFormBundle](http://rdir.io/dit) - A collection of useful form types and extensions.
 * [IvoryOrderedFormBundle](http://rdir.io/CmH) - Provides a form ordering support.
 * [LexikFormFilterBundle](http://rdir.io/LWA) - Lexik Form Filter bundle.

## Service Container

 * [JMSDiExtraBundle](http://rdir.io/oZu) - Provides Advanced Dependency Injection Features.
 * [PHP-DI](http://rdir.io/sji) - The dependency injection container for humans.
 * [KutnyAutowiringBundle](http://rdir.io/B7o) - a bundle providing autowiring for service arguments.

## Development

 * [BeforeAfterControllersHooksBundle](http://rdir.io/UKu) - Provides "@BeforeHook" and "@AfterHook" Annotations support for Symfony Controllers.
 * [JMSDebuggingBundle](http://rdir.io/7LS) - Provides advanced debugging tools.
 * [LadybugBundle](http://rdir.io/zNg) - The Simple and Extensible PHP Dumper
 * [LiipCodeBundle](http://rdir.io/Yc7) - A set of Symfony2 console commands to help developers deal with the various ways of identifying classes, templates, bundles, services, etc.
 * [ListenersDebugCommandBundle](http://rdir.io/uOy) - A console command to debug listeners.
 * [PUGXGeneratorBundle](http://rdir.io/PgI) - An enhancement of SensioGeneratorBundle.
 * [SandboxBundle](http://rdir.io/ecG) - Overriding controller logic & response in a Sandbox environment.
 * [SecurityDebugCommandBundle](http://rdir.io/4G3) - Symfony 2 commands to debug the security component.
 * [TagDebugCommandBundle](http://rdir.io/7oC) - Integrate TagDebug library for inspecting and debugging tags
 * [TwigReflectionBundle](http://rdir.io/qeI) - Displays what's in Twig.
 * [WebfactoryExceptionsBundle](http://rdir.io/7hw) - Easily develop custom, user-friendly error pages.
 * [WebProfilerExtraBundle](http://rdir.io/9VN) - Adding routing, container, assetic & twig information in the web profiler.
 * [XhprofBundle](http://rdir.io/lGI) - XHProf bundle.
 
## Assets Management

 * [assetic-extra-bundle](http://rdir.io/Edy) - Asset Directory filter for Assetic.
 * [AsseticMinifierBundle](http://rdir.io/B5s) - An assetic minifier in pure PHP for CSS and JS files.
 * [FkrCssURLRewriteBundle](http://rdir.io/C1q) - A small assetic filter to fix all url paths at css documents to correct urls.
 * [IgorwFileServeBundle](http://rdir.io/j8m) - Bundle for serving protected files.
 * [JmikolaJsAssetsHelperBundle](http://rdir.io/AYX) - Exposes the AssetsHelper service from Symfony2's templating component to JavaScript, allowing relative or absolute asset URI's to be generated client-side.
 * [KachkaevAssetsVersionBundle](http://rdir.io/wed) - Automates the process of updating assets version.
 * [SalvaJshrinkBundle](http://rdir.io/USj) - This bundle integrate jshrink library as Assetic filter and twig extension.
 * [SpritesBundle](http://rdir.io/Ss3) - Bundle for the Sprites library.
 * [ZakharovviHumansTxtBundle](http://rdir.io/IqU) - Generate humans.txt file from git repository.

## Queues

 * [GearmanBundle](http://rdir.io/IDk) - A bundle intended to provide an easy way to support developers who need to use job queues.
 * [JMSJobQueueBundle](http://rdir.io/EHz) - Allows to schedule console commands as jobs.
 * [LeezyPheanstalkBundle](http://rdir.io/9nW) - Bundle for Pheanstalk, PHP client for beanstalkd queue.
 * [qpush-bundle](http://rdir.io/LA9) - The QPush Bundle relies on the Push Queue model of Message Queues to provide asynchronous processing in your application.
 * [RabbitMqBundle](http://rdir.io/vyZ) - RabbitMQ bundle.

## Internationalization

 * [JMSI18nRoutingBundle](http://rdir.io/aRx) - Bundle for multilingual websites to support international routes.
 * [JMSTranslationBundle](http://rdir.io/AEj) - Translate your website with ease - extract messages & translate them via a web-based UI.
 * [LuneticsLocaleBundle](http://rdir.io/QL5) - Guess the visitor’s locale from different parameters.
 * [TimezoneBundle](http://rdir.io/Afz) - Serverside Timezone detection

## Payments Management

 * [CartBundle](http://rdir.io/NeB) - High quality cart for developers.
 * [JMSPaymentCoreBundle](http://rdir.io/HZG) - This bundle provides the foundation for various payment plugins.
 * [JMSPaymentPaypalBundle](http://rdir.io/vaq) - Payment Bundle providing access to the PayPal API.
 * [PayumBundle](http://rdir.io/NxL) - Rich payment solutions for symfony2. Paypal, Stripe, Payex, Authorize.NET, Be2bill, Klarna, recurring paymens, instant notifications and many more

## Monitoring

 * [SoclozMonitoringBundle](http://rdir.io/2Cu) - A monitoring bundle for production servers

## Administration

 * [AdmingeneratorGeneratorBundle](http://rdir.io/6ET) - Admingenerator for Symfony2, parse generator.yml files to build classes
 * [EasyAdminBundle](http://rdir.io/LNW) - Simple admin generator for Symfony applications
 * [SonataAdminBundle](http://rdir.io/Ofm) - AdminBundle - The missing Symfony2 Admin Generator

## Miscellaneous

 * [AnhTaggableBundle](http://rdir.io/Jym) - Bundle provides integration of doctrine-extensions-taggable, adds form types for editing tag and tagging.
 * [APYBreadcrumbTrailBundle](http://rdir.io/pat) - This bundle provides annotations and PHP methods to generate a breacrumb trail.
 * [APYDataGridBundle](http://rdir.io/P9e) - Datagrid Bundle.
 * [BazingaFakerBundle](http://rdir.io/1F3) - Put the awesome Faker library into the Symfony2 DIC and populate your database with fake data.
 * [BazingaGeocoderBundle](http://rdir.io/Feg) - Integration of the Geocoder library.
 * [BCCMyrrixBundle](http://rdir.io/cr0) - Myrrix is a recommendation engine built on Apache Mahout libraries.
 * [BeelabTagBundle](http://rdir.io/YlJ) - A simple implementation of tags for Symfony2 and Doctrine ORM.
 * [BGBarcodeBundle](http://rdir.io/NHN) - Bundle for barcode rendering using our barcode generator base library.
 * [BlogBundle](http://rdir.io/Y1w) - Simple blog module.
 * [BreadcrumbsBundle](http://rdir.io/7ZW) - A small breadcrumbs bundle.
 * [BrowscapBundle](http://rdir.io/7Be) - Bundle to access the browscap information.
 * [CacheToolBundle](http://rdir.io/k0Y) - Bundle to integrate cachetool library in Symfony2 (Clear acp/opcache from the command line)
 * [CarbonBundle](http://rdir.io/vR3) - This bundle provides an opportunity to convert Request data into Carbon objects.
 * [CheckBundles](http://rdir.io/Cw6) - Checks installed but not activated in AppKernel bundles.
 * [CloudBackupBundle](http://rdir.io/LVh) - Be able to backup your database(s) and upload it to the cloud.
 * [ConsoleBundle](http://rdir.io/kJG) - Commandline interface in browser.
 * [ControllerExtraBundle](http://rdir.io/Kij) - Controller extras bundle.
 * [EmbedlyBundle](http://rdir.io/K8z) - Bundle for the embed.ly library.
 * [FeatureToggleBundle](http://rdir.io/e11) - Configure your feature toggling in Symfony2 by adding some simple tags to twig and extending it's configuration.
 * [ffmpeg-bundle](http://rdir.io/8wJ) - This bundle provides a simple wrapper for the PHP_FFmpeg library, exposing the library as a Symfony service.
 * [FlorianvSwapBundle](http://rdir.io/5yT) - This Bundle integrates the Swap library.
 * [godfather](http://rdir.io/Ak9) - A library for the strategy pattern in PHP.
 * [GoogleBundle](http://rdir.io/2ZH) - Bundle for Google Analytics.
 * [guzzle-bundle](http://rdir.io/NwY) - Integrates Guzzle.
 * [highcharts-bundle](http://rdir.io/Epf) - Integrates PHP Highcharts.
 * [HTMLPurifierBundle](http://rdir.io/U8P) - HTML Purifier is a standards-compliant HTML filter library written in PHP.
 * [IbrowsWizardAnnotationBundle](http://rdir.io/pkC) - Give's a Symfony2 controller a simple wizard/workflow with annotations.
 * [KayueEssenceBundle](https://github.com/kayue/KayueEssenceBundle) - This bundle integrates the Essence library (an oEmbed library) into Symfony 2.
 * [KitpagesDataGridBundle](http://rdir.io/ySJ) - This bundle provides a simple datagrid bundle.
 * [KnpMarkdownBundle](http://rdir.io/VSO) - Wrapper for PHP markdown.
 * [KnpSnappyBundle](http://rdir.io/zI8) - Easily create PDF and images by converting html using webkit.
 * [LiipUrlAutoConverterBundle](http://rdir.io/wg2) - Add a Twig Extension for templates with a new filter for automatically converting urls and emails in a string to html links.
 * [metrics](http://rdir.io/t18) - Simple library that abstracts different metrics collectors.
 * [Mobile-Detect](http://rdir.io/8Fo) - Mobile_Detect is a lightweight PHP class for detecting mobile devices (including tablets).
 * [MobileDetectBundle](http://rdir.io/wGS) - Bundle for detect mobile devices, manage mobile view and redirect to the mobile and tablet version.
 * [MultiParamBundle](http://rdir.io/a3o) - MultiParam Annotation Bundle.
 * [OneupUploaderBundle](http://rdir.io/Fv1) - Provides server implementations for several multi file uploader.
 * [phone-number-bundle](http://rdir.io/MzR) - Integrates libphonenumber.
 * [ProblematicIPHunterBundle](http://rdir.io/Dne) - Request IP Reporting for Symfony 2.
 * [rss-atom-bundle](http://rdir.io/cwc) - RSS and Atom Bundle.
 * [Search-SphinxsearchBundle](http://rdir.io/lsa) - Sphinx search bundle.
 * [shorturl-bundle](http://rdir.io/iC8) - Provides short URLs for your project.
 * [sphinx-realtime-bundle](http://rdir.io/FTf) - A bundle which automatically syncs Doctrine entities to a Sphinx real-time index.
 * [SphinxsearchBundle](http://rdir.io/gA7) - Provide to use Sphinx search.
 * [StringGeneratorBundle](http://rdir.io/THV) - This bundle allows you to automatically generate a unique random string on an entity property, useful for creating keys.
 * [TbbcCacheBundle](http://rdir.io/aO3) - Cache abstraction bundle.
 * [TemplatedUriBundle](http://rdir.io/sSA) - Expose the hautelook/TemplatedUriRouter.
 * [timeline-bundle](http://rdir.io/lmH) - Symfony2 bundle to make timeline
 * [TimelineBundle](http://rdir.io/zBJ) - Integrates timeline.
 * [TransmissionBundle](http://rdir.io/npQ) - Bundle for Transmission API client.
 * [versioning-bundle](http://rdir.io/oHN) - Simple way to version (semantic versioning 2.0.0).
 * [WhiteOctoberPagerfantaBundle](http://rdir.io/6bp) - Bundle to use Pagerfanta.
 * [WidopFrameworkExtraBundle](http://rdir.io/svB) - Adds annotation configuration for Controller classes.
 * [WozbeRedirectBundle](http://rdir.io/2l4) - A short bundle to manage many domains.

## Third Party APIs
 * [CoopTilleulsOvhBundle](http://rdir.io/3AK) - OVH SDK integration in Symfony.
 * [GordalinaMixpanelBundle](http://rdir.io/5G8) - Mixpanel integration in Symfony2
 * [SwarrotBundle](http://rdir.io/suI) - A bundle for swarrot integration.

## Reading

 * [Assets Cache Busting in Symfony](http://rdir.io/BCe)
 * [High Performance Websites with Symfony2](http://rdir.io/g94)
 * [Rationally boost your symfony2 application with caching tips and monitoring](http://rdir.io/dNX)
 * [Symfony - project tamed](http://rdir.io/DI6)
 * [Symfony2 cheat sheet](http://rdir.io/OoH)

## Distributions

* [KnpLabs RAD Edition](http://rdir.io/9uO)
* [Kunstmaan Bundles Standard Edition](http://rdir.io/DQS)
* [Liip RAD Edition](http://rdir.io/yIa)
* [Symfony Biga Edition](http://rdir.io/28s)
* [Symfony Bootstrap Edition](http://rdir.io/RB6)
* [Symfony CMF Standard Edition](http://rdir.io/F2t)
* [Symfony EmberJs Edition](http://rdir.io/Shl)
* [Symfony Emptier Edition](http://rdir.io/5yi)
* [Symfony Empty Edition](http://rdir.io/7R1)
* [Symfony Micro Edition](http://rdir.io/iYv)
* [Symfony Nerdery Edition](http://rdir.io/cu6)
* [Symfony REST Edition](http://rdir.io/QEN)
* [Symfony Sonata Edition](http://rdir.io/lYI)
* [Symfony Standard Edition](http://rdir.io/tVe)
