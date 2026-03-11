# pdfocr2

Windows desktop OCR app for turning scanned PDFs and images into searchable, editable documents.

## What It Does

- Opens scanned PDFs and image files in a GUI.
- Runs OCR with PaddleOCR.
- Supports higher-accuracy text correction with VLM providers.
- Lets you review and edit detected text and boxes before export.
- Exports searchable PDF output.
- Supports batch processing for multiple files.
- Falls back to CPU OCR automatically if GPU OCR is unavailable.

## Main Features

- GUI-based OCR workflow for Windows
- Searchable PDF export
- Text and bounding-box editing
- Batch OCR
- Optional GPU acceleration with CUDA
- Optional VLM-based refinement through LM Studio or external APIs

## Download

Preferred release assets:

- `pdfocr2-package-win64.7z.001`
- `pdfocr2-package-win64.7z.002`

Keep both files in the same folder before extraction.

## Setup

1. Install [7-Zip](https://www.7-zip.org/) if needed.
2. Put `pdfocr2-package-win64.7z.001` and `pdfocr2-package-win64.7z.002` in the same folder.
3. Open `pdfocr2-package-win64.7z.001` with 7-Zip.
4. Extract the package to a normal writable folder such as `C:\tools\pdfocr2`.

## How To Use

1. Run `pdfocr2.exe`.
2. Open a scanned PDF or image file.
3. Start OCR.
4. Review and fix text or boxes in the editor if needed.
5. Export as a searchable PDF.

## VLM Features

VLM-based refinement is optional.

- Local: LM Studio with a compatible vision model
- External: OpenAI, Google Gemini, or Anthropic Claude APIs

If no VLM provider is configured, standard OCR still works.

## Notes

- This package is a Windows `onedir` distribution. Keep extracted files together.
- GPU OCR may be used when CUDA is available.
- If GPU initialization fails, the app falls back to CPU OCR automatically.
- For best results, use clear scans with sufficient resolution.

## SHA256

- `pdfocr2-package-win64.7z.001`
  `B144C2F30D48DCB2FC1C84EA24C40D3EB4404065B277A12BDB48304560423677`
- `pdfocr2-package-win64.7z.002`
  `1D352D17A671C56B383C5E3092B5F58A9A473A026B67A8E17EFC74B1EE150BF5`
