# instrument-cad
dVRK Instrument CAD files

## Disclaimer

**These instrument models were created using models provided by Intuitive Surgical, Inc. 
They are provided "as is", without warranty of any kind, express or implied, including but 
not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. 
In no event shall the authors or copyright holders be liable for any claim, damages or other liability, 
whether in an action of contract, tort or otherwise, arising from, out of or in connection with the design 
or the use or other dealings in these instrument models.**


## Included dVRK Instruments

| # | Folder Name                  | Description                                          |
|---|------------------------------|------------------------------------------------------|
| 1 | `Large_Needle_Driver_420009` | Large Needle Driver for da Vinci Si surgical system  |


## Folder Architecture

```bash
.
├── <Tool Name>             # Tool Instrument Folder
│   ├── high_res            # High Resolution Meshes 
│   │   ├── ...             # Model Mesh OBJ & MTL Files 
│   ├── low_res             # Low Resolution Meshes
│   │   ├── ...             # Model Mesh OBJ & MTL  Files 
│   └── README.md           # README file for the tool instrument
├── ...                     # Other Tools
└── README.md               # Overall README files
```

## File Explanation

- OBJ: File includes the information of the 3D Mesh Volume
- MTL: File includes the information of the textures





