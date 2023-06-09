---
layout: post
title: "CZ HL2 Texture Reuse"
date: 2022-10-25
permalink: /CZ-HL2_Texture_Reuse
---

<h1> What? </h1>

<p>Counter-Strike: Condition Zero contains numerous downscaled Half-Life 2 textures from a version prior to the Leak. These aren't the only ones, but these numbered series of textures have an advantage. </p>

<p>When Half-Life 2's textures were converted, they did so in a useful way. The numbers are their position in the folder that was converted in alphabetical order. This means that not only do we have the textures, we know their relative positions as well. This allows insight into how the texture folders changed, and helps confirm if certain textures are a match.  </p>

<p>The numbers indicate how many "places" are between each row of textures. When they are inconsistent, this indicates the texture order has undergone changes. This doesn't work if the texture "series" (metalwall --> metalladder, IE) changes, which is indicated by a "Series break" row. </p>

<h1> Info </h1> 

<table style="max-width:1100px;">
<thead>
<tr>
<th>CZ</th>
<th>HL2</th>
</tr>
</thead>
<tbody>
<tr>
<td>cncrt010  <br /> <img src="assets/czhl2/cncrt010_result.png" alt=""></td>
<td>concretefloor004a <br /> <img src="assets/czhl2/concretefloor004a.png" alt=""></td>
</tr>
<tr>
<td>+4</td>
<td>+4</td>
</tr>
<tr>
<td>cncrt014  <br /> <img src="assets/czhl2/cncrt014_result.png" alt=""></td>
<td>concretefloor008a <br /> <img src="assets/czhl2/concretefloor008a.png" alt=""></td>
</tr>
<tr>
<td>+13</td>
<td>+13</td>
</tr>
<tr>
<td>cncrt027 <br /> <img src="assets/czhl2/cncrt027_result.png" alt=""></td>
<td>concretefloor016a <br /> <img src="assets/czhl2/concretefloor016a.png" alt=""></td>
</tr>
<tr>
<td>+11</td>
<td><strong>+5?</strong></td>
</tr>
<tr>
<td>cncrt038 <br /> <img src="assets/czhl2/cncrt038_result.png" alt=""></td>
<td>concretefloor023a <br /> <img src="assets/czhl2/concretefloor023a.png" alt=""></td>
</tr>
<tr>
<td>+15</td>
<td>+15</td>
</tr>
<tr>
<td>cncrt053 <br /> <img src="assets/czhl2/cncrt053_result.png" alt=""></td>
<td>concretefloor029a <br /> <img src="assets/czhl2/concretefloor029a.png" alt=""></td>
</tr>
<tr>
<td>Series break</td>
<td></td>
</tr>
<tr>
<td>cncrt094 <br /> <img src="assets/czhl2/cncrt094_result.png" alt=""></td>
<td>concretestair002a <br /> <img src="assets/czhl2/concretestair002a.png" alt=""></td>
</tr>
<tr>
<td>Series break</td>
<td></td>
</tr>
<tr>
<td>cncrt102 <br /> <img src="assets/czhl2/cncrt102_result.png" alt=""></td>
<td>concretewall001b <br /> <img src="assets/czhl2/concretewall001b%201.png" alt=""></td>
</tr>
<tr>
<td>cncrt103 <br /> <img src="assets/czhl2/cncrt103_result.png" alt=""></td>
<td>concretewall001c <br /> <img src="assets/czhl2/concretewall001c.png" alt=""></td>
</tr>
<tr>
<td>+4</td>
<td>+4</td>
</tr>
<tr>
<td>cncrt107 <br /> <img src="assets/czhl2/cncrt107_result.png" alt=""></td>
<td>concretewall002b <br /> <img src="assets/czhl2/concretewall002b.png" alt=""></td>
</tr>
<tr>
<td>cncrt108 <br /> <img src="assets/czhl2/cncrt108_result.png" alt=""></td>
<td>concretewall002c <br /> <img src="assets/czhl2/concretewall002c.png" alt=""></td>
</tr>
<tr>
<td>+18</td>
<td>+18</td>
</tr>
<tr>
<td>cncrt126 <br /> <img src="assets/czhl2/cncrt126_result.png" alt=""></td>
<td>concretewall010a <br /> <img src="assets/czhl2/concretewall010a.png" alt=""></td>
</tr>
<tr>
<td>cncrt149 <br /> <img src="assets/czhl2/cncrt149_result.png" alt=""></td>
<td>concretewall015a <br /> <img src="assets/czhl2/concretewall015a.png" alt=""></td>
</tr>
<tr>
<td>cncrt150 <br /> <img src="assets/czhl2/cncrt150_result.png" alt=""></td>
<td>concretewall015b <br /> <img src="assets/czhl2/concretewall015b.png" alt=""></td>
</tr>
<tr>
<td>cncrt151 <br /> <img src="assets/czhl2/cncrt151_result.png" alt=""></td>
<td>concretewall015c <br /> <img src="assets/czhl2/concretewall015c.png" alt=""></td>
</tr>
<tr>
<td>+21</td>
<td>+46?</td>
</tr>
<tr>
<td>cncrt172 <br /> <img src="assets/czhl2/cncrt172_result.png" alt=""></td>
<td>concretewall020a <br /> <img src="assets/czhl2/dev_concretewall020a.png" alt=""> also <br> concretewall027a <br /> <img src="assets/czhl2/concretewall027a.png" alt=""></td>
</tr>
<tr>
<td>+4</td>
<td>+4</td>
</tr>
<tr>
<td>cncrt176 <br /> <img src="assets/czhl2/cncrt176_result.png" alt=""></td>
<td>concretewall022a? No orig.</td>
</tr>
<tr>
<td>+24</td>
<td>+24</td>
</tr>
<tr>
<td>cncrt200 <br /> <img src="assets/czhl2/cncrt200_result.png" alt=""></td>
<td>concretewall032a <br /> <img src="assets/czhl2/concretewall032a.png" alt=""></td>
</tr>
<tr>
<td>+5</td>
<td>+5</td>
</tr>
<tr>
<td>cncrt205 <br /> <img src="assets/czhl2/cncrt205_result.png" alt=""></td>
<td>concretewall036a <br /> <img src="assets/czhl2/concretewall036a.png" alt=""></td>
</tr>
<tr>
<td>+5</td>
<td>+5</td>
</tr>
<tr>
<td>cncrt210 <br /> <img src="assets/czhl2/cncrt210_result.png" alt=""></td>
<td>concretewall037d <br /> <img src="assets/czhl2/concretewall037d.png" alt=""></td>
</tr>
<tr>
<td>+6</td>
<td>+6</td>
</tr>
<tr>
<td>cncrt216 <br /> <img src="assets/czhl2/cncrt216_result.png" alt=""></td>
<td>concretewall040a <br /> <img src="assets/czhl2/concretewall040a.png" alt=""></td>
</tr>
<tr>
<td>+8</td>
<td>+11?</td>
</tr>
<tr>
<td>cncrt224 <br /> <img src="assets/czhl2/cncrt224_result.png" alt=""></td>
<td>concretewall042a <br /> <img src="assets/czhl2/concretewall042a.png" alt=""></td>
</tr>
<tr>
<td>+11</td>
<td>+11</td>
</tr>
<tr>
<td>cncrt235 <br /> <img src="assets/czhl2/cncrt235_result.png" alt=""></td>
<td>concretewall047c <br /> <img src="assets/czhl2/concretewall047c.png" alt=""></td>
</tr>
<tr>
<td>+3</td>
<td>+3 (049a assumed, but missing)</td>
</tr>
<tr>
<td>cncrt238 <br /> <img src="assets/czhl2/cncrt238_result.png" alt=""></td>
<td>concretewall049b <br /> <img src="assets/czhl2/concretewall049b.png" alt=""></td>
</tr>
<tr>
<td>+11</td>
<td>+10?</td>
</tr>
<tr>
<td>cncrt249 <br /> <img src="assets/czhl2/cncrt249_result.png" alt=""></td>
<td>concretewall057b <br /> <img src="assets/czhl2/concretewall057b.png" alt=""></td>
</tr>
<tr>
<td>cncrt250 <br /> <img src="assets/czhl2/cncrt250_result.png" alt=""></td>
<td>concretewall057c <br /> <img src="assets/czhl2/concretewall057c.png" alt=""></td>
</tr>
<tr>
<td>+15</td>
<td>+19?</td>
</tr>
<tr>
<td>cncrt265 <br /> <img src="assets/czhl2/cncrt265_result.png" alt=""></td>
<td>concretewall062a <br /> <img src="assets/czhl2/concretewall062a.png" alt=""></td>
</tr>
<tr>
<td>+2</td>
<td>+2 (063a missing</td>
</tr>
<tr>
<td>cncrt267 <br /> <img src="assets/czhl2/cncrt267_result.png" alt=""></td>
<td>concretewall064a <br /> <img src="assets/czhl2/concretewall064a.png" alt=""></td>
</tr>
<tr>
<td>+8</td>
<td>+8</td>
</tr>
<tr>
<td>cncrt275 <br /> <img src="assets/czhl2/cncrt275_result.png" alt=""></td>
<td>concretewall065a <br /> <img src="assets/czhl2/concretewall065a.png" alt=""></td>
</tr>
<tr>
<td>cncrt276 <br /> <img src="assets/czhl2/cncrt276_result.png" alt=""></td>
<td>concretewall065b <br /> <img src="assets/czhl2/concretewall065b.png" alt=""></td>
</tr>
<tr>
<td>Series break</td>
<td></td>
</tr>
<tr>
<td>mtl008 <br /> <img src="assets/czhl2/mtl008_result.png" alt=""></td>
<td>metalceiling008a <br /> <img src="assets/czhl2/metalceiling008a.png" alt=""></td>
</tr>
<tr>
<td>+46</td>
<td>+19? (+20 with missing metalceiling009a)</td>
</tr>
<tr>
<td>mtl054 <br /> <img src="assets/czhl2/mtl054_result.png" alt=""></td>
<td>metaldoor018a <br /> <img src="assets/czhl2/metaldoor018a.png" alt=""></td>
</tr>
<tr>
<td>+36</td>
<td>+53?</td>
</tr>
<tr>
<td>mtl114 <br /> <img src="assets/czhl2/mtl114_result.png" alt=""></td>
<td>metaldoor059a <br /> <img src="assets/czhl2/metaldoor059a.png" alt=""></td>
</tr>
<tr>
<td>+60</td>
<td>+58?</td>
</tr>
<tr>
<td>mtl186 <br /> <img src="assets/czhl2/mtl186_result.png" alt=""></td>
<td>metalhull006c <br /> <img src="assets/czhl2/metalhull006c.png" alt=""></td>
</tr>
<tr>
<td>+2</td>
<td>+2</td>
</tr>
<tr>
<td>mtl188 <br /> <img src="assets/czhl2/mtl188_result.png" alt=""></td>
<td>metalhull007b <br /> <img src="assets/czhl2/metalhull007b%201.png" alt=""></td>
</tr>
<tr>
<td>+21</td>
<td>+21</td>
</tr>
<tr>
<td>mtl209 <br /> <img src="assets/czhl2/mtl209_result.png" alt=""></td>
<td>metalladder001a <br /> <img src="assets/czhl2/metalladder001a.png" alt=""></td>
</tr>
<tr>
<td><strong>+44</strong></td>
<td>+13?</td>
</tr>
<tr>
<td>mtl253 <br /> <img src="assets/czhl2/mtl253_result.png" alt=""></td>
<td>metalpipe012a <br /> <img src="assets/czhl2/metalpipe012a.png" alt=""></td>
</tr>
<tr>
<td>mtl259 <br /> <img src="assets/czhl2/mtl259_result.png" alt=""></td>
<td>metalroof005b <br /> <img src="assets/czhl2/metalroof005b.png" alt=""></td>
</tr>
<tr>
<td>mtl260 <br /> <img src="assets/czhl2/mtl260_result.png" alt=""></td>
<td>? metalroof006a (old)?<br /> <img src="assets/czhl2/metalroof006a_height.png" alt=""></td>
</tr>
<tr>
<td>Series break (roof textures after this newer?)</td>
<td></td>
</tr>
<tr>
<td>mtl261 <br /> <img src="assets/czhl2/mtl261_result.png" alt=""></td>
<td>metalstair001a <br /> <img src="assets/czhl2/metalstair001a.png" alt=""></td>
</tr>
<tr>
<td>+2</td>
<td>+1 (originally metalstair001b?</td>
</tr>
<tr>
<td>mtl263 <br /> <img src="assets/czhl2/mtl263_result.png" alt=""></td>
<td>metalstair002a <br /> <img src="assets/czhl2/metalstair002a.png" alt=""></td>
</tr>
<tr>
<td>Series break</td>
<td></td>
</tr>
<tr>
<td>mtl286 <br /> <img src="assets/czhl2/mtl286_result.png" alt=""></td>
<td>metalwall004a <br /> <img src="assets/czhl2/metalwall004a.png" alt=""></td>
</tr>
<tr>
<td>+31</td>
<td>+27?</td>
</tr>
<tr>
<td>mtl317 <br /> <img src="assets/czhl2/mtl317_result.png" alt=""></td>
<td>metalwall015a <br /> <img src="assets/czhl2/metalwall015a.png" alt=""></td>
</tr>
<tr>
<td>+23</td>
<td>+31?</td>
</tr>
<tr>
<td>mtl340 <br /> <img src="assets/czhl2/mtl340_result.png" alt=""></td>
<td>metalwall029a <br /> <img src="assets/czhl2/metalwall029a%201.png" alt=""></td>
</tr>
<tr>
<td>+32</td>
<td>+27?</td>
</tr>
<tr>
<td>mtl372 <br /> <img src="assets/czhl2/mtl372_result.png" alt=""></td>
<td>metalwall047a <br /> <img src="assets/czhl2/metalwall047a.png" alt=""> </td>
</tr>
<tr>
<td>+10</td>
<td>+8?</td>
</tr>
<tr>
<td>mtl382 <br /> <img src="assets/czhl2/mtl382_result.png" alt=""></td>
<td>metalwall053a <br /> <img src="assets/czhl2/metalwall053a.png" alt=""></td>
</tr>
<tr>
<td>+3</td>
<td>+2?</td>
</tr>
<tr>
<td>mtl385 <br /> <img src="assets/czhl2/mtl385_result.png" alt=""></td>
<td>metalwall054b <br /> <img src="assets/czhl2/metalwall054b.png" alt=""></td>
</tr>
<tr>
<td>+4</td>
<td>+3?</td>
</tr>
<tr>
<td>mtl389 <br /> <img src="assets/czhl2/mtl389_result.png" alt=""></td>
<td>metalwall054e <br /> <img src="assets/czhl2/metalwall054e.png" alt=""></td>
</tr>
<tr>
<td>+13</td>
<td>+5?</td>
</tr>
<tr>
<td>mtl402 <br /> <img src="assets/czhl2/mtl402_result.png" alt=""></td>
<td>metalwall056b <br /> <img src="assets/czhl2/metalwall056b.png" alt=""></td>
</tr>
<tr>
<td>mtl403 <br /> <img src="assets/czhl2/mtl403_result.png" alt=""></td>
<td>metalwall056c <br /> <img src="assets/czhl2/metalwall056c.png" alt=""></td>
</tr>
<tr>
<td>mtl407 <br /> <img src="assets/czhl2/mtl407_result.png" alt=""></td>
<td></td>
</tr>
<tr>
<td>mtl413 <br /> <img src="assets/czhl2/mtl413_result%201.png" alt=""></td>
<td>metalwall061f <br /> <img src="assets/czhl2/metalwall061f.png" alt=""></td>
</tr>
<tr>
<td>+5</td>
<td>+5</td>
</tr>
<tr>
<td>mtl418 <br /> <img src="assets/czhl2/mtl418_result%201.png" alt=""></td>
<td>metalwall064a <br /> <img src="assets/czhl2/metalwall064a.png" alt=""></td>
</tr>
<tr>
<td>+65</td>
<td>+21</td>
</tr>
<tr>
<td>mtl483 <br /> <img src="assets/czhl2/mtl483_result.png" alt=""></td>
<td>metalwall085a <br /> <img src="assets/czhl2/metalwall085a.png" alt=""></td>
</tr>
<tr>
<td>plstr123 <br /> <img src="assets/czhl2/plstr123_result.png" alt=""></td>
<td>???</td>
</tr>
<tr>
<td>plstr174 <br /> <img src="assets/czhl2/plstr174_result%201.png" alt=""></td>
<td>plasterwall034d <br /> <img src="assets/czhl2/plasterwall034d.png" alt=""></td>
</tr>
<tr>
<td>plstr201 <br /> <img src="assets/czhl2/plstr201_result.png" alt=""></td>
<td>???</td>
</tr>
<tr>
<td>plstr222 <br /> <img src="assets/czhl2/plstr222_result.png" alt=""></td>
<td>???</td>
</tr>
<tr>
<td>plstr233 <br /> <img src="assets/czhl2/plstr233_result.png" alt=""></td>
<td>plasterwall047b <br /> <img src="assets/czhl2/plasterwall047b.png" alt=""></td>
</tr>
<tr>
<td>rock034 <br /> <img src="assets/czhl2/rock034_result.png" alt=""></td>
<td>rockwall012b <br /> <img src="assets/czhl2/rockwall012b.png" alt=""></td>
</tr>
<tr>
<td>tile017 <br /> <img src="assets/czhl2/tile017_result.png" alt=""></td>
<td>???</td>
</tr>
<tr>
<td>tile023 <br /> <img src="assets/czhl2/tile023_result.png" alt=""></td>
<td>???</td>
</tr>
<tr>
<td>wood093 <br /> <img src="assets/czhl2/wood093_result.png" alt=""></td>
<td>woodfloor006a <br /> <img src="assets/czhl2/woodfloor006a.png" alt=""></td>
</tr>
<tr>
<td>wood136 <br /> <img src="assets/czhl2/wood136_result.png" alt=""></td>
<td>woodwall009a <br /> <img src="assets/czhl2/woodwall009a.png" alt=""></td>
</tr>
<tr>
<td>wood155 <br /> <img src="assets/czhl2/wood155_result.png" alt=""></td>
<td>woodwall022a <br /> <img src="assets/czhl2/woodwall022a.png" alt=""></td>
</tr>
<tr>
<td>wood180 <br /> <img src="assets/czhl2/wood180_result.png" alt=""></td>
<td>???</td>
</tr>
</tbody>
</table>
