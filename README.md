
<img src="img/logo.png" width="80" align="left">

# OpenManuscript

This is OpenManuscript, a text-based data format specification for writing
fiction in an organized, hassle-free way that frees you up to be your most
creative!

For more information about this specification, contact david@dhrogers.com.

Project tweets at [@OpenMSProject](https://twitter.com/openmsproject)

## Introduction

This is a specification for OpenManuscript v1.0, a database for an ASCII text-based workflow for writing fiction, managing drafts, and creating [fiction manuscripts](https://www.shunn.net/format/story.html).

The OpenManuscript format separates the data from the applications 
that edit, display or print it, which is a very powerful mechanism for invention

A writer can use a variety of tools instead of being locked into using a specific one. Software developers can create new tools, and writers can adopt them without any data conversion, or loss of work.

## Advantages of OpenManuscript

The advantages of the OpenManuscript format are many:

- OpenManuscript is an open standard, using only common text-based file formats.
  - Currenly, only **JSON** and **Markdown** files are needed. We use
    [Gruber's](https://daringfireball.net/projects/markdown/) specification of
    markdown.
- The author can use favorite tools for editing text, **markdown** and **JSON** files.
- Build a manuscript from scenes and chapters. 
  - The basic unit of writing in OpenManuscript is the **scene**, so an author can easily compare different chapter/scene oders, combinations and versions with minimal effort. This is a huge advantage over writing workflows based on, for example, Microsoft Word.

## The Overall Workflow for OpenManuscript
<p align="center">
<img src="img/workflow.png" width="65%">
</p>

As shown in the above diagram, the OpenManuscript format is used by any
compliant editing tool (one that can save text-only files) in the day to day 
work, and when it's time to look at
a final manuscript, share it as a specific document type (Word, PDF, etc.) or
publish it as a final product (ebook, etc.), the writer uses another tool to
create that product.

Using a text-based standard means
the author needn't worry that the format will be unreadable down the road
because the software you used outdated, no longer reads that version of the
output, or is simply gone. 

This repository includes a specification document, simple tools, and an example of the file format.

Keep it simple.






