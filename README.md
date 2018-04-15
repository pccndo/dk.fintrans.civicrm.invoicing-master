# dk.fintrans.civicrm.invoicing-master
CiviCRM export to Invoicing
===========================

This extension extract the defined group of mmbers and send it for invoicing by either ACH, CreditCard or other paymentmethods.

Warnings
========


Requirements
============

- CiviCRM >= 4.4 (previous versions untested)

Installation
============

Install as any other regular CiviCRM extension:

1- Download this extension and unpack it in your 'extensions' directory.

2- Enable the extension from CiviCRM -> Administer -> System -> Extensions.

Report mails
============

Support
=======

support@fintrans.eu

Todo
====

* Propose a new hook to CiviCRM for a cleaner postProcess implementation (incl. mail).
* Add OpenDocument (LibreOffice) support.
* Add admin settings form to enable excel/opendocument formats?
* Compare performance with tinybutstrong/tbs library?

License
=======

(C) 2018 PC <pc@fintrans.eu>

Distributed under the terms of the GNU Affero General public license (AGPL).
See LICENSE.txt for details.


