# LEADTOOLS Document Converter Demo for .NET Framework

This demo falls under the [license located here.](./LICENSE.md)

Powered by patented artificial intelligence and machine learning algorithms, [LEADTOOLS is a collection of award-winning document, medical, multimedia, and imaging SDKs](https://www.leadtools.com)

This .NET WinForms demo showcases the [LEADTOOLS Document Converter SDK](https://www.leadtools.com/sdk/document/document-converter) and allows users to: 

- Convert to and from any document or raster image format
  - Adobe Acrobat PDF and PDF/A
  - Microsoft Office DOC/DOCX, XLS/XLSX, PPT/PPTX, PST, EML, MSG, and XPS formats
  - CAD formats such as DXF, DWG, and DWF
  - TIFF, JPEG, PNG, EXIF, BMP, and hundreds more raster image formats
  - Plain Text, RTF, HTML, MOBI, ePUB, and more
  - IBM AFP, MO:DCA, IOCA, and PTOCA
- Automatically OCR raster images to searchable documents
- Convert a document format to a different document format with 100% accuracy without the need to OCR

With the Document Converter demo, you convert raster and document formats. It is ideal for Enterprise Content Management (ECM), document archival, and document normalization development.

## Set Up

In order to use any LEADTOOLS functionality, you must have a valid license. You can obtain a fully functional 30-day license [from our website](https://www.leadtools.com/downloads).

Locate the `RasterSupport.SetLicense(licenseFilePath, developerKey);` line in the application and modify the code to point to use your new license and key.

Open the csproj file in Visual Studio. Build the project to restore the [LEADTOOLS NuGet packages](https://www.leadtools.com/downloads/nuget).

## Use

To Convert a folder of files using the Document Converter:

1. Specify the file extension to convert from the source folder (use *.* for all files in the folder), specify the input folder, specify the output folder, and indicate if you want to stop the conversion process on the first error

2. Hit OK and select the OCR Engine to use

3. In the Document Converter Options indicate the output format and options to use then hit OK to start the conversion

## Resources

Website: <https://www.leadtools.com/>

Download Full Evaluation: <https://www.leadtools.com/downloads>

Documentation: <https://www.leadtools.com/help/leadtools/v20/dh/to/introduction.html>

Technical Support: <https://www.leadtools.com/support/chat>

[nuget-profile]: https://www.nuget.org/profiles/LEADTOOLS
