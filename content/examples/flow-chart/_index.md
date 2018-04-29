---
title: Flow Chart
weight: 5
---


{{<mermaid align="left">}}
graph LR;
    A[Hard edge] -->|Link text| B(Round edge)
    B --> C{Decision}
    C -->|One| D[Result one]
    C -->|Two| E[Result two]
{{< /mermaid >}}

## Flowchart example
	{{</*mermaid align="left"*/>}}
	graph LR;
		A[Hard edge] -->|Link text| B(Round edge)
    	B --> C{Decision}
    	C -->|One| D[Result one]
    	C -->|Two| E[Result two]
    {{</* /mermaid */>}}
