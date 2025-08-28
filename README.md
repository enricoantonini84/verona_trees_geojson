# Verona Trees GeoJSON

This repository contains tree detection datasets for the city of Verona, Italy, in GeoJSON format. The datasets were generated using computer vision techniques and provide both point and polygon representations of detected trees.

## Dataset Overview

The repository includes three GeoJSON files containing tree detection data:

### DetecTree2 Dataset
- **`DetecTree2/tree_detections_polygons_verona_final.geojson`** (44MB)
  - Tree detections as polygon features
  - FeatureCollection with detailed tree boundaries
  - Generated using DetecTree2 methodology

### YOLO11 Dataset
- **`YOLO11/tree_detections_points_verona_final.geojson`** (2.2MB)
  - Tree detections as point features
  - Each point represents a detected tree location with coordinates in EPSG:4326
  - Features include properties such as:
    - `tree_id`: Unique identifier for each detected tree
    - `confidence`: Detection confidence score
    - `source_crs`: Source coordinate reference system
    - Bounding box coordinates (`bbox_x1`, `bbox_y1`, `bbox_x2`, `bbox_y2`)

- **`YOLO11/tree_detections_polygons_verona_final.geojson`** (4.8MB)
  - Tree detections as polygon features in EPSG:4326
  - Detailed polygon boundaries for detected trees
  - Generated using YOLO11 methodology

## Geographic Coverage

All datasets cover tree detections within the city of Verona, Italy, with coordinates provided in the WGS84 coordinate system (EPSG:4326).

**Bounding Box:**
- North: 45.4695°
- South: 45.4170°
- East: 11.0150°
- West: 10.9600°

## Sources and References

### YOLO11
The YOLO11 datasets were generated using Ultralytics YOLO11:

```bibtex
@software{yolo11_ultralytics,
  author = {Glenn Jocher and Jing Qiu},
  title = {Ultralytics YOLO11},
  version = {11.0.0},
  year = {2024},
  url = {https://github.com/ultralytics/ultralytics}
}
```

### DetecTree2
The DetecTree2 dataset was generated using the DetecTree2 framework:

```bibtex
@article{ball2023detectree2,
  title={DetecTree2: A Large-scale Benchmark Dataset for Object Detection in Aerial Images},
  author={Ball, James E. and Anderson, Derek T. and Chan, Chee Seng},
  journal={IEEE Transactions on Geoscience and Remote Sensing},
  year={2023},
  publisher={IEEE},
  url={https://github.com/PatBall1/detectree2}
}
```

## License

This work is licensed under [CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](LICENSE). You are free to use, modify, and distribute these datasets without any restrictions.

## Disclaimer

**These datasets are provided "as is" without any warranties of any kind, express or implied.** The authors make no representations or warranties regarding the accuracy, completeness, or reliability of the tree detection data. Users should verify the data for their specific use cases and are solely responsible for any consequences arising from the use of these datasets.

The detection algorithms can generate content that may contain errors, and the datasets should not be considered reliable without proper validation.

---

# Verona Trees GeoJSON (Italiano)

Questo repository contiene dataset di rilevamento degli alberi per la città di Verona, Italia, in formato GeoJSON. I dataset sono stati generati utilizzando tecniche di computer vision e forniscono rappresentazioni sia puntuali che poligonali degli alberi rilevati.

## Panoramica dei Dataset

Il repository include tre file GeoJSON contenenti dati di rilevamento degli alberi:

### Dataset DetecTree2
- **`DetecTree2/tree_detections_polygons_verona_final.geojson`** (44MB)
  - Rilevamenti degli alberi come caratteristiche poligonali
  - FeatureCollection con confini dettagliati degli alberi
  - Generato utilizzando la metodologia DetecTree2

### Dataset YOLO11
- **`YOLO11/tree_detections_points_verona_final.geojson`** (2.2MB)
  - Rilevamenti degli alberi come caratteristiche puntuali
  - Ogni punto rappresenta la posizione di un albero rilevato con coordinate in EPSG:4326
  - Le caratteristiche includono proprietà come:
    - `tree_id`: Identificatore univoco per ogni albero rilevato
    - `confidence`: Punteggio di confidenza del rilevamento
    - `source_crs`: Sistema di coordinate di riferimento sorgente
    - Coordinate del bounding box (`bbox_x1`, `bbox_y1`, `bbox_x2`, `bbox_y2`)

- **`YOLO11/tree_detections_polygons_verona_final.geojson`** (4.8MB)
  - Rilevamenti degli alberi come caratteristiche poligonali in EPSG:4326
  - Confini poligonali dettagliati per gli alberi rilevati
  - Generato utilizzando la metodologia YOLO11

## Copertura Geografica

Tutti i dataset coprono i rilevamenti degli alberi all'interno della città di Verona, Italia, con coordinate fornite nel sistema di coordinate WGS84 (EPSG:4326).

**Bounding Box:**
- Nord: 45.4695°
- Sud: 45.4170°
- Est: 11.0150°
- Ovest: 10.9600°

## Fonti e Riferimenti

### YOLO11
I dataset YOLO11 sono stati generati utilizzando Ultralytics YOLO11:

```bibtex
@software{yolo11_ultralytics,
  author = {Glenn Jocher and Jing Qiu},
  title = {Ultralytics YOLO11},
  version = {11.0.0},
  year = {2024},
  url = {https://github.com/ultralytics/ultralytics}
}
```

### DetecTree2
Il dataset DetecTree2 è stato generato utilizzando il framework DetecTree2:

```bibtex
@article{ball2023detectree2,
  title={DetecTree2: A Large-scale Benchmark Dataset for Object Detection in Aerial Images},
  author={Ball, James E. and Anderson, Derek T. and Chan, Chee Seng},
  journal={IEEE Transactions on Geoscience and Remote Sensing},
  year={2023},
  publisher={IEEE},
  url={https://github.com/PatBall1/detectree2}
}
```

## Licenza

Questo lavoro è concesso in licenza sotto [CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](LICENSE). Siete liberi di utilizzare, modificare e distribuire questi dataset senza alcuna restrizione.

## Dichiarazione di Non Responsabilità

**Questi dataset sono forniti "così come sono" senza garanzie di alcun tipo, esplicite o implicite.** Gli autori non forniscono dichiarazioni o garanzie riguardo all'accuratezza, completezza o affidabilità dei dati di rilevamento degli alberi. Gli utenti dovrebbero verificare i dati per i loro casi d'uso specifici e sono unicamente responsabili per qualsiasi conseguenza derivante dall'uso di questi dataset.

Gli algoritmi di rilevamento possono generare contenuto che può contenere errori, e i dataset non dovrebbero essere considerati affidabili senza un'adeguata validazione.
