# Schema Types

<details>
  <summary><strong>Table of Contents</strong></summary>

  * [Query](#query)
  * [Mutation](#mutation)
  * [Objects](#objects)
    * [Player](#player)
  * [Enums](#enums)
    * [Team](#team)
  * [Scalars](#scalars)
    * [Boolean](#boolean)
    * [ID](#id)
    * [String](#string)

</details>

## Query
<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="query.findall">findAll</strong></td>
<td valign="top">[<a href="#player">Player</a>]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.findbyid">findById</strong></td>
<td valign="top"><a href="#player">Player</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="query.findbyteam">findByTeam</strong></td>
<td valign="top">[<a href="#player">Player</a>]</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">team</td>
<td valign="top"><a href="#team">Team</a>!</td>
<td></td>
</tr>
</tbody>
</table>

## Mutation
<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="mutation.createplayer">createPlayer</strong></td>
<td valign="top"><a href="#player">Player</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">name</td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">team</td>
<td valign="top"><a href="#team">Team</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">city</td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
</tbody>
</table>

## Objects

### Player

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong id="player.id">id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="player.name">name</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="player.team">team</strong></td>
<td valign="top"><a href="#team">Team</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong id="player.city">city</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
</tbody>
</table>

## Enums

### Team

<table>
<thead>
<tr>
<th align="left">Value</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><strong>CSK</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>MI</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>RCB</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>DC</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>GT</strong></td>
<td></td>
</tr>
</tbody>
</table>

## Scalars

### Boolean

The `Boolean` scalar type represents `true` or `false`.

### ID

The `ID` scalar type represents a unique identifier, often used to refetch an object or as key for a cache. The ID type appears in a JSON response as a String; however, it is not intended to be human-readable. When expected as an input type, any string (such as `"4"`) or integer (such as `4`) input value will be accepted as an ID.

### String

The `String` scalar type represents textual data, represented as UTF-8 character sequences. The String type is most often used by GraphQL to represent free-form human-readable text.

