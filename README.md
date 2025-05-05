**YOLO Segmentation Project**

This project focuses on applying **YOLO-based image segmentation** for analyzing object detection performance across different datasets.

**Project Workflow:**
✅ Run segmentation tests using YOLO on a prepared list of images, saving results including:
  – Segmented images
  – Bounding boxes
  – Mask data (in JSON format, one JSON per image)

✅ Train the provided dataset (e.g., `part-autolabeled-5`) to evaluate which object parts are detected well and which are not.
  – Visualize around 5–10 sample cases of both good and poor detections.

✅ Find and use an external dataset, train YOLOv8 on it, and compare detection performance similar to the original dataset.

**Tools and Notes:**

* Requires YOLOv8 and integration with Roboflow (API Key needed).
* Useful for exploring segmentation performance, model strengths/weaknesses, and cross-dataset generalization.

---

