---
title: Using Default PCL XL Fonts
author: windows-driver-content
description: Using Default PCL XL Fonts
MS-HAID:
- 'nt5gpd\_bd5e43fb-7eab-449e-aea8-b96485cb8cc4.xml'
- 'print.using\_default\_pcl\_xl\_fonts'
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: 8e6abae5-c86f-4cfc-a379-2dd3f8810474
keywords: ["PCL XL vector graphics WDK Unidrv , default fonts", "default PCL XL fonts", "fonts WDK PCL XL"]
---

# Using Default PCL XL Fonts


## <a href="" id="ddk-using-default-pcl-xl-fonts-gg"></a>


If you want to include the standard PCL XL fonts, you should include the standard resource DLL, *pclxl.dll*, that is part of the cab file. The following line, which should appear in the GPD, uses the \*ResourceDLL attribute to specify the resource DLL to be used.

```
*ResourceDLL: "pclxl.dll"
```

The default PCL XL fonts that Unidrv supports are listed in the following table:

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Font Name</th>
<th>Font File</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>&quot;Albertus Medium&quot;</p></td>
<td><p>ALBERTR.UFM</p></td>
</tr>
<tr class="even">
<td><p>&quot;Albertus Extra Bold&quot;</p></td>
<td><p>ALBERTX.UFM</p></td>
</tr>
<tr class="odd">
<td><p>&quot;Antique Olive&quot;</p></td>
<td><p>AOLIVEB.UFM</p>
<p>AOLIVEI.UFM</p>
<p>AOLIVER.UFM</p></td>
</tr>
<tr class="even">
<td><p>&quot;Arial&quot;</p></td>
<td><p>ARIALB.UFM</p>
<p>ARIALI.UFM</p>
<p>ARIALJ.UFM</p>
<p>ARIALR.UFM</p></td>
</tr>
<tr class="odd">
<td><p>&quot;ITC Benguiat&quot;</p></td>
<td><p>BENGUATB.UFM</p>
<p>BBENGUATJ.UFM</p>
<p>BENGUATJ.UFM</p>
<p>BENGUATR.UFM</p></td>
</tr>
<tr class="even">
<td><p>&quot;ITC Bookman Demi&quot;</p></td>
<td><p>BOOKMANB.UFM</p>
<p>BOOKMANJ.UFM</p></td>
</tr>
<tr class="odd">
<td><p>&quot;ITC Bookman Light&quot;</p></td>
<td><p>BOOKMANI.UFM</p>
<p>BOOKMANR.UFM</p></td>
</tr>
<tr class="even">
<td><p>&quot;Brougham&quot;</p></td>
<td><p>BROGHAMB.UFM</p>
<p>BROGHAMI.UFM</p>
<p>BROGHAMJ.UFM</p>
<p>BROGHAMR.UFM</p></td>
</tr>
<tr class="odd">
<td><p>&quot;CG Omega&quot;</p></td>
<td><p>CGOMEGAB.UFM</p>
<p>CGOMEGAI.UFM</p>
<p>CGOMEGAJ.UFM</p>
<p>CGOMEGAR.UFM</p></td>
</tr>
<tr class="even">
<td><p>&quot;CG Times&quot;</p></td>
<td><p>CGTIMESB.UFM</p>
<p>CGTIMESI.UFM</p>
<p>CGTIMESJ.UFM</p>
<p>CGTIMESR.UFM</p></td>
</tr>
<tr class="odd">
<td><p>&quot;Clarendon Condensed&quot;</p></td>
<td><p>CLARCD.UFM</p></td>
</tr>
<tr class="even">
<td><p>&quot;Coronet&quot;</p></td>
<td><p>CORONETR.UFM</p></td>
</tr>
<tr class="odd">
<td><p>&quot;Courier&quot;</p></td>
<td><p>COURIERB.UFM</p>
<p>COURIERI.UFM</p>
<p>COURIERJ.UFM</p>
<p>COURIERR.UFM</p></td>
</tr>
<tr class="even">
<td><p>&quot;Garamond&quot;</p></td>
<td><p>GARMONDB.UFM</p>
<p>GARMONDI.UFM</p>
<p>GARMONDJ.UFM</p>
<p>GARMONDR.UFM</p></td>
</tr>
<tr class="odd">
<td><p>&quot;Letter Gothic&quot;</p></td>
<td><p>LETGOTHB.UFM</p>
<p>LETGOTHI.UFM</p>
<p>LETGOTHR.UFM</p></td>
</tr>
<tr class="even">
<td><p>&quot;Marigold&quot;</p></td>
<td><p>MARGOLDR.UFM</p></td>
</tr>
<tr class="odd">
<td><p>&quot;Times New Roman&quot;</p></td>
<td><p>TIMESNRB.UFM</p>
<p>TIMESNRI.UFM</p>
<p>TIMESNRJ.UFM</p>
<p>TIMESNRR.UFM</p></td>
</tr>
<tr class="even">
<td><p>&quot;Univers Condensed&quot;</p></td>
<td><p>UNIVERCB.UFM</p>
<p>UNIVERCI.UFM</p>
<p>UNIVERCJ.UFM</p>
<p>UNIVERCR.UFM</p></td>
</tr>
<tr class="odd">
<td><p>&quot;Univers&quot;</p></td>
<td><p>Universa.UFM</p>
<p>UNIVERSB.UFM</p>
<p>Universc.UFM</p>
<p>Universd.UFM</p>
<p>Universe.UFM</p>
<p>UNIVERSI.UFM</p>
<p>UNIVERSJ.UFM</p>
<p>UNIVERSR.UFM</p>
<p>UNIVERSR.UFM</p></td>
</tr>
<tr class="even">
<td><p>&quot;W Dingbats&quot;</p></td>
<td><p>WDINGBAT.UFM</p></td>
</tr>
<tr class="odd">
<td><p>&quot;Wingdings&quot;</p></td>
<td><p>WINGDING.UFM</p></td>
</tr>
<tr class="even">
<td><p>&quot;Symbol&quot;</p></td>
<td><p>SYMBOL.UFM</p></td>
</tr>
</tbody>
</table>

 

 

 


--------------------
[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bprint\print%5D:%20Using%20Default%20PCL%20XL%20Fonts%20%20RELEASE:%20%289/1/2016%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")


