# Tesseract.js 번들 경로

GitHub Pages 등 정적 환경에서 오프라인 실행을 위해 다음 파일을 `assets/tesseract/`에 배치하세요.

- `tesseract.min.js`
- `worker.min.js`
- `tesseract-core.wasm.js`
- `tesseract-core.wasm`
- `tessdata/eng.traineddata`

위 파일들은 다음 배포본에서 받을 수 있습니다.
- https://unpkg.com/tesseract.js@5.1.0/dist/
- https://unpkg.com/tesseract.js-core@5.1.0/
- https://tessdata.projectnaptha.com/4.0.0/eng.traineddata

로컬 파일이 없을 경우 앱은 CDN 경로로 자동 폴백하지만, 오프라인 및 iOS Safari 안정성을 위해 가능하면 위 파일을 리포지토리에 포함해주세요.
