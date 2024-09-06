# DSI Interview - Telecom Parsers!

DMI provides their customers software so that they can use to upload their Telecom bills
and then see the bill breakdown displayed in a Web interface.

In order to do this DMI takes Telecom bills in PDF, CSV, and other file formats,
and then converts them all into structured data, which is then applied a few transformations,
and finally stored in the Database.

A big part of this work requires that we parse through unstructured text, extract information
using regexes, or simple string operations, and then store that information in simple objects

Below you are given an array that contains the text of a parsed PDF, your job is to display
the following information in a structured manner:
  - Invoice Number
  - Invoice Period Start
  - Invoice Period End
  - All non-zero Charges, along with their usage information
  - The Invoice total

Make sure that the sum of all charges needs to equal the invoice total.
