 `Component` `Physics`



(NOTE) Defines the collision volume for a capsule defined by a height and radius. A capsule can be thought of as a cylinder with spherical end caps.

|Methods|Properties|Base Classes|Derived Classes|
|---|---|---|---|
|[ Constructor](https://github.com/dragonCASTjosh/PlasmaDocs/blob/master/code_reference/class_reference/capsulecollider.markdown#capsulecollider-void)|[ Direction](https://github.com/dragonCASTjosh/PlasmaDocs/blob/master/code_reference/class_reference/capsulecollider.markdown#direction-plasma-engine-do)|[collider](https://github.com/dragonCASTjosh/PlasmaDocs/blob/master/code_reference/class_reference/collider.markdown)| |
| |[ Height](https://github.com/dragonCASTjosh/PlasmaDocs/blob/master/code_reference/class_reference/capsulecollider.markdown#height-plasma-engine-docum)| | |
| |[ Radius](https://github.com/dragonCASTjosh/PlasmaDocs/blob/master/code_reference/class_reference/capsulecollider.markdown#radius-plasma-engine-docum)| | |
| |[ ScalingMode](https://github.com/dragonCASTjosh/PlasmaDocs/blob/master/code_reference/class_reference/capsulecollider.markdown#scalingmode-plasma-engine)| | |
| |[ WorldCylinderHeight](https://github.com/dragonCASTjosh/PlasmaDocs/blob/master/code_reference/class_reference/capsulecollider.markdown#worldcylinderheight-plasma)| | |
| |[ WorldRadius](https://github.com/dragonCASTjosh/PlasmaDocs/blob/master/code_reference/class_reference/capsulecollider.markdown#worldradius-plasma-engine)| | |


 #  Properties


---  
 #  Direction : [AxisDirection](https://github.com/dragonCASTjosh/PlasmaDocs/blob/master/code_reference/enum_reference.markdown#axisdirection)

> The direction that the height is defined along. Allows the user to change whether the capsule's height is along the local-space x, y, or z axis.
> ``` lang=cpp, name=Lightning
> var Direction : AxisDirection


---  
 #  Height : [real](https://github.com/dragonCASTjosh/PlasmaDocs/blob/master/code_reference/lightning_base_types/real.markdown)

> The local space distance from the center of one sphere to another.
> ``` lang=cpp, name=Lightning
> var Height : Real


---  
 #  Radius : [real](https://github.com/dragonCASTjosh/PlasmaDocs/blob/master/code_reference/lightning_base_types/real.markdown)

> The local space radius of the spheres at the capsule edges.
> ``` lang=cpp, name=Lightning
> var Radius : Real


---  
 #  ScalingMode : [CapsuleScalingMode](https://github.com/dragonCASTjosh/PlasmaDocs/blob/master/code_reference/enum_reference.markdown#capsulescalingmode)

> How should non-uniform scale affect the capsules size. Should a scale of 2 on the height axis double the total capsule size or should it double the capsule height?
> ``` lang=cpp, name=Lightning
> var ScalingMode : CapsuleScalingMode


---  
 #  WorldCylinderHeight : [real](https://github.com/dragonCASTjosh/PlasmaDocs/blob/master/code_reference/lightning_base_types/real.markdown)

 `read-only`

> The full height of the capsule's cylinder after the scale is applied (world distance from one sphere to another).
> ``` lang=cpp, name=Lightning
> var WorldCylinderHeight : Real


---  
 #  WorldRadius : [real](https://github.com/dragonCASTjosh/PlasmaDocs/blob/master/code_reference/lightning_base_types/real.markdown)

 `read-only`

> The radius of the sphere caps after scale is applied.
> ``` lang=cpp, name=Lightning
> var WorldRadius : Real


---  
 #  Methods


---  
 #  CapsuleCollider : Void

 `constructor`

> 
> |Name|Type|Description|
> |---|---|---|
> ``` lang=cpp, name=Lightning
> function CapsuleCollider()
> ``` 


---  
 

 