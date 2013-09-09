Scrapy
======

Use scrapy framework to parse movie links


This will create a tutorial directory with the following contents:
==================================================================

YSMI/
    scrapy.cfg
    YSMI/
        __init__.py
        items.py
        pipelines.py
        settings.py
        spiders/
            __init__.py
            ysmi_spider.py
            ...
These are basically:

scrapy.cfg: the project configuration file
YSMI/: the project’s python module, you’ll later import your code from here.
YSMI/items.py: the project’s items file.
YSMI/pipelines.py: the project’s pipelines file.
YSMI/settings.py: the project’s settings file.
YSMI/spiders/: a directory where you’ll later put your spiders.



