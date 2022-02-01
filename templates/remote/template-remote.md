![Version badge](https://img.shields.io/badge/Version-1.0.0-blue.svg?maxAge=2592000)

**CSV remote template**
=======================

This template aims to keep this page updated: 
https://pt.teamlyzer.com/companies/remote-companies

Table of contents
=================

  * [CSV remote template](#csv-remote-template)
  * [Table of contents](#table-of-contents)
  * [Introduction](#introduction)
  * [Columns](#columns)
    * [id](#id)
    * [msg](#msg)
    * [ts](#ts)
    * [source](#source)
    * [company_id](#company_id)
    * [working_model](#working_model)
    
**Introduction**
================

Use this file when you have some information relevant to `remote-companies` page. There are mainly two situations.  

Please note:

- (1) You need to update outdated info. In this case, you should copy the past information from the `remote-companies` page and add context to the new one.
- (2) You need insert info about a new company.   

After submit, please reset to original csv template.

**Columns**
===========

id
--

* **Description** 
`Mandatory. Incremental order starting at 1.`

* **Required** 
`id=[integer]`

msg
---

* **Description** 
`Mandatory. The text that you want to insert for each company. If it's an update you may need to add context and probably keep past information too.`

* **Required** 
`string=[Empresa de AI norte-americana tem uma pequena equipa a trabalhar a partir de Portugal em regime 100% remoto.]`

ts
--

* **Description** 
`Mandatory. Date of this file.`

* **Required** 
`string=[2021-09-22 14:05:29+00]`

source
------

* **Description** 
`Mandatory. Source of the info. It can be a link or plain text.`

* **Required** 
`string=[Relato directo de colaborador.]`

company_id 
----------

* **Description** 
`Mandatory. The ID of the company to which the entry refers.` 

* **Source** 
https://drive.google.com/drive/u/2/folders/13g5ABgsO135zt2OrYnkgROKpgq91tEpM

* **Required** 
`id=[integer]`

working_model 
-------------

* **Description** 
`Mandatory. Map the working model using the following options.`

* **Required** 
`id=[integer]`

 * **Options** 
 
    | Id | Description |
    | ------ | ------ |
    | 1 | Full remote |
    | 2 | Remote first |
    | 3 | Híbrido |
    | 4 | Escritório |
