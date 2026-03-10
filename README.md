# pdfocr2

Windows distribution for `pdfocr2`.

## Download

Preferred release assets:

- `pdfocr2-package-win64.7z.001`
- `pdfocr2-package-win64.7z.002`

Legacy assets may also exist, but the `pdfocr2-package-win64` set is the current package.

Keep both files in the same folder before extraction.

## Extract

Use 7-Zip and open `pdfocr2-package-win64.7z.001`.
7-Zip will automatically read `.002` and extract the full package.

After extraction, run:

- `pdfocr2.exe`

## Notes

- This package is built as a Windows `onedir` distribution.
- GPU OCR may be used when CUDA is available.
- If GPU OCR initialization fails, the app now falls back to CPU OCR automatically.

## SHA256

- `pdfocr2-package-win64.7z.001`
  `B144C2F30D48DCB2FC1C84EA24C40D3EB4404065B277A12BDB48304560423677`
- `pdfocr2-package-win64.7z.002`
  `1D352D17A671C56B383C5E3092B5F58A9A473A026B67A8E17EFC74B1EE150BF5`
