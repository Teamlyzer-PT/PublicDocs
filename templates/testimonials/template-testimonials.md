![Version badge](https://img.shields.io/badge/Version-1.0.0-blue.svg?maxAge=2592000)

**CSV testimonial template**
=======================

This template aims to keep these pages updated: 
https://pt.teamlyzer.com/companies/xxx/testimonials

Table of contents
=================

  * [CSV testimonial template](#csv-testimonial-template)
  * [Table of contents](#table-of-contents)
  * [Introduction](#introduction)
  * [Columns](#columns)
    * [id](#id)
    * [company_id](#company_id)
    * [ts](#ts)
    * [iframe](#iframe)
    
**Introduction**
================

Use this file when you find out a new testimonial on social media. Usually we want posts from Linkedin or videos on Youtube.

After submit, please reset to original csv template.

**Columns**
===========

id
--

* **Description** 
`Mandatory. Incremental order starting at 1.`

* **Required** 
`id=[integer]`

company_id 
----------

* **Description** 
`Mandatory. The ID of the company to which the entry refers.` 

* **Source** 
https://drive.google.com/drive/u/2/folders/13g5ABgsO135zt2OrYnkgROKpgq91tEpM

* **Required** 
`id=[integer]`

ts
--

* **Description** 
`Mandatory. Date of the post.`

* **Required** 
`string=[2021-09-22 14:05:29+00]`

iframe
------

* **Description** 
`Mandatory. If it's a LinkedIn post you have to click on upper right corner (•••) and choose embed this post. Sometimes you can select only the video or image of that post. If a Youtube video please click share and then embed`

* **Required** 
`string=[Iframe code]`
