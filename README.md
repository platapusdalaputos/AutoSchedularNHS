# AutoSchedularNHS
Extracts calendar appointments from microsoft outlook API (MAPI) and Schedules staff appointments without overlap given a variety of constraints

Within most organisations scheduling is required based on specific needs. A diagnostic Medical physics departemnt within the NHS, contracts work for various units (hospitals) within specifc regions. Work mainly consists of the commissioning and testing of Diagnostic machinary, which is carried on a semi-annual and annual basis depending on the machine.

This autoschedular schedules testing based on the dates the various units provide. Units frequently provide overlappaing dates which clash with other units. 

This autoschedular consists of a few constraints: The compentancy of staff (Junior/Senior), The amount 
