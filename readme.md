Follow ttn activation/setup instructions - https://ttn.fyi/activate/

Upload the Arduino IDE Passthrough sketch to enable direct serial access from USB to RN2483A
With Passthrough - In Serial Monitor select “Both NL & CR” and “115200 baud” in the bottom right dropdowns and send a command like: mac get deveui

Update the RN2483A firmware v1.0.5 using microchip java utility in Windows
If firmware fails then use Module > Add and try again
https://www.microchip.com/Developmenttools/ProductDetails/dv164140-1

The RESET switch is inside the case, outside is only the BUTTON switch

To find nearby gateways http://ttnmapper.org/

Then use the Console/Data tab from a browser to see received messages/payload

Version History
26/10/19 Initial text.
