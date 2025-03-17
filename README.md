Program uses Dymo SDK to connect to and send xml in order to print qr codes generated from an excel upload file from the client.

Helpful document for XML Label formatting: https://docs.google.com/document/d/1Hb_1qDJmnaWM7-AfKr6LguLxh2nAoWWo_zR2ZmSq4vA/edit?pli=1&tab=t.0#heading=h.1en9qkdfndsz 

Dymo SDK References: https://github.com/dymosoftware/dymo-connect-framework/blob/master/README.md

For this to work, user must install Dymo Connect software and the Dymo SDK.

Excel file format is specific to this solution. Part Number should be in cell A1. Serial numbers will start from A2. This solution is flexible to the qty of serial numbers inputted. Max SN values per label to not exceed 35. QR Code will exceed the bounds of the border

Excel file format: PartNumber SN1 SN2 SN3 SN4 SN5 SN6 SN7 SN8 SN9 SN10 SN11 SN12 SN13 SN14 SN15 SN16 SN17 SN18 SN19 SN20
