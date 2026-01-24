# WebPII Models

Trained baseline models for WebPII: A Synthetic Benchmark for Visual PII Detection in E-commerce Web Interfaces.

## Available Models

### WebRedact
- **Resolution**: 640×640
- **Performance**: 0.753 mAP@50 on Test_Cross-Company
- **Latency**: ~20ms (CPU, real-time at 30 FPS)
- **Files**: `nano640.bin`, `nano640.xml`

### WebRedact-large
- **Resolution**: 1280×1280
- **Performance**: 0.842 mAP@50 on Test_Cross-Company
- **Latency**: ~312ms (CPU, near-real-time at 3 FPS)
- **Files**: `small1280.bin`, `small1280.xml`

## Model Format

Models are provided in OpenVINO Intermediate Representation (IR) format for CPU inference. Load using OpenVINO Runtime for inference on images.

## Classes

Both models detect two classes:
- **text**: Text-based PII elements
- **image**: Product images and visual identifiers

## Citation

```bibtex
@inproceedings{anonymous2026webpii,
  title={WebPII: A Synthetic Benchmark for Visual PII Detection in E-commerce Web Interfaces},
  author={Anonymous Authors},
  booktitle={International Conference on Machine Learning},
  year={2026}
}
```
