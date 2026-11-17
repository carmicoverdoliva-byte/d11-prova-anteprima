# Prova D11 · Anteprima live

Pagina di prova (non è l'app) del progetto open source e non commerciale **Plant Intelligence**: misura se un modello di
riconoscimento delle piante può girare nel browser dell'iPhone.

- Indirizzo: https://carmicoverdoliva-byte.github.io/d11-prova-anteprima/ (modello originale, 173 MB) ·
  https://carmicoverdoliva-byte.github.io/d11-prova-anteprima/?variante=int8 (modello compresso, 87 MB)
- **Privacy:** le immagini della fotocamera **non lasciano il telefono**. La pagina scarica solo il motore ONNX Runtime
  Web (da cdn.jsdelivr.net, con controllo d'integrità) e il modello (da huggingface.co, con controllo SHA-256).
- **Modello:** BioCLIP v1 (Imageomics, MIT); conversione ONNX
  [m3r1al/naturalist-bioclip-v1](https://huggingface.co/m3r1al/naturalist-bioclip-v1) (MIT); versione compressa
  [carmineverdoliva-byte/d11-bioclip-int8](https://huggingface.co/carmineverdoliva-byte/d11-bioclip-int8), versione ca03b3a.
- **Impronte delle piante:** calcolate da foto iNaturalist con licenza aperta, autori in `crediti-riferimenti.md`.
  Le foto non sono pubblicate qui.
- Codice della pagina: licenza MIT (`LICENSE`).
