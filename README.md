# Wind Power Plant & Wind Turbine DTDL Models

This repository includes DTDL models for wind farms and wind turbines based on the [IEC 61400-25](https://webstore.iec.ch/publication/22813) standard. These models can be used to create digital twin instances in [Azure Digital Twins](https://azure.microsoft.com/services/digital-twins/) directly or through the [XMPro](https://xmpro.com) No Code Application Development Platform.  

<img src="/images/DTDL-Wind-Turbine-Diagram.png" style="zoom:55%;" />

![](/images/Wind-Turbine - Red Status.png)

<center>Example wind turbine Digital Twin in XMPro using the open-source DTDL models and data from Azure Digital Twins

## Contains

### Common Information

| File        | Description                                       |
| ----------- | ------------------------------------------------- |
| LLN0_.json  | Logical Node Zero                                 |
| LPHD_.json  | Physical Device Information                       |


### Wind Power Plant

| File        | Description                                       |
| ----------- | ------------------------------------------------- |
| WPPD_.json  | Wind power plant general information              |
| WALM_.json  | Wind power plant alarm information                |
| WAPC_.json  | Wind power plant active power control information |                                                
| WMET_.json  | Wind power plant meteorological information       |
| WRPC_.json  | Wind power plant reactive power control           |


### Wind Turbine

| File        | Description                                       |
| ----------  | ------------------------------------------------- |
| WTUR_.json  | Wind turbine general information                  |
| WCNV_.json  | Wind turbine converter information                |
| WGEN1_.json | Wind turbine 1 generator information              |
| WGEN2_.json | Wind turbine 2 generator information              |
| WROT_.json  | Wind turbine rotor information                    |
| WTOW_.json  | Wind turbine tower information                    |
| WTRF_.json  | Wind turbine transformer information              |
| WTRM_.json  | Wind turbine transmission information             |
| WYAW_.json  | Wind turbine yawing information                   |
| WNAC_.json  | Wind turbine nacelle information                  |
| WAVL_.json  | Wind turbine availability information             |

### Not Supported*

| File        | Description                                       |
| ----------  | ------------------------------------------------- |
| WALG_.json  | Wind turbine analogue log information             |
| WSLG_.json  | Wind turbine state log information                |
| WREP_.json  | Wind turbine report information                   |

*These files are currently not supported in Azure Digital Twin, but can be used in Time Series Insights and XMPro.

## Support

This repository was created by @XMPro in collaboration with the [Digital Twin Consortium](https://www.digitaltwinconsortium.org). For assistance or feature requests, contact support@xmpro.com.
