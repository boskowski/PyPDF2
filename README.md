# PyPDF2 (Legacy 1.26.0 Maintenance Fork)

> [!NOTE]
> This repository is a legacy compatibility fork of **PyPDF2 1.26.0**. It retains the classic 1.x API for projects unable to upgrade to `pypdf` 3.x+, while incorporating critical stability patches:
> - **`PdfFileWriter` stream guard:** Prevents `AttributeError` when sweeping indirect references without a stream object.
> - **Document permissions:** Backported support for inspecting and setting PDF document permission flags.
>
> For modern projects starting fresh, use upstream [`pypdf`](https://github.com/py-pdf/pypdf).

### Installation

```bash
pip install git+https://github.com/boskowski/PyPDF2.git@v1.26.0.post1
```

---

PyPDF2 is a pure-python PDF library capable of
splitting, merging together, cropping, and transforming
the pages of PDF files. It can also add custom
data, viewing options, and passwords to PDF files.
It can retrieve text and metadata from PDFs as well
as merge entire files together.

Homepage  
http://mstamy2.github.io/PyPDF2/

## Examples

Please see the `Sample_Code` folder.

## Documentation

Documentation is available at  
https://pythonhosted.org/PyPDF2/


## FAQ
Please see  
http://mstamy2.github.io/PyPDF2/FAQ.html


## Tests
PyPDF2 includes a test suite built on the unittest framework. All tests are located in the "Tests" folder.
Tests can be run from the command line by:

```bash
python -m unittest Tests.tests
```
