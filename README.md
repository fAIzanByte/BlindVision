# BlindVision
BlindVision is an adversarial patch generation framework designed to test and enhance the robustness of computer vision models.

It utilizes a pretrained ResNet-50, optimizing a randomly initialized texture through gradient ascent to maximize the target class score. By integrating custom masking techniques and leveraging PyTorch's efficient GPU acceleration, BlindVision demonstrates how carefully crafted perturbations can significantly alter model predictions, providing insights into potential vulnerabilities in deep learning systems.
