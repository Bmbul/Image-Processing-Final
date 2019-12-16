# Stage 1

Before image extraction a Gaussian kernel with sigma 2 is used. After the extraction, a mean filter is used in order to soften the noise.

This is the kernel used for any picture before extracting layers.

| 0 | 1 | 2 | 3 | 4 |
|:--------:| -------------:| -------------:|  -------------:|  -------------:|
| 2 | 2 | 2 | 2 | 2 |
| 2 | 5 | 5 | 5	| 2 |
| 2 | 5 | 25 | 5 | 2 |
| 2 | 5 | 5 | 5	| 2 |
| 2 | 2 | 2 | 2	| 2 |

Besides critical rotation of the head, the result of the extracted layers remain stable (besides the boy with red shirt). Availability of smiles doesn't have significant effect on corresponding layers.
