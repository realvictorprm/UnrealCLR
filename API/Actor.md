### [UnrealEngine.Framework](./UnrealEngine-Framework.md 'UnrealEngine.Framework')
## Actor Class
The base class of an object that can be placed or spawned in a level  
```csharp
public class Actor :
System.IEquatable<UnrealEngine.Framework.Actor>
```
Inheritance [System.Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object 'System.Object') &#129106; Actor  

Derived  
&#8627; [AmbientSound](./AmbientSound.md 'UnrealEngine.Framework.AmbientSound')  
&#8627; [Brush](./Brush.md 'UnrealEngine.Framework.Brush')  
&#8627; [Camera](./Camera.md 'UnrealEngine.Framework.Camera')  
&#8627; [Controller](./Controller.md 'UnrealEngine.Framework.Controller')  
&#8627; [GameModeBase](./GameModeBase.md 'UnrealEngine.Framework.GameModeBase')  
&#8627; [LevelScript](./LevelScript.md 'UnrealEngine.Framework.LevelScript')  
&#8627; [Light](./Light.md 'UnrealEngine.Framework.Light')  
&#8627; [Pawn](./Pawn.md 'UnrealEngine.Framework.Pawn')  
&#8627; [TriggerBase](./TriggerBase.md 'UnrealEngine.Framework.TriggerBase')  

Implements [System.IEquatable&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1 'System.IEquatable`1')[Actor](./Actor.md 'UnrealEngine.Framework.Actor')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1 'System.IEquatable`1')  
### Constructors
- [Actor(string, UnrealEngine.Framework.Blueprint)](./Actor-Actor(string_Blueprint).md 'UnrealEngine.Framework.Actor.Actor(string, UnrealEngine.Framework.Blueprint)')
### Properties
- [BlockInput](./Actor-BlockInput.md 'UnrealEngine.Framework.Actor.BlockInput')
- [CreationTime](./Actor-CreationTime.md 'UnrealEngine.Framework.Actor.CreationTime')
- [ID](./Actor-ID.md 'UnrealEngine.Framework.Actor.ID')
- [InputComponent](./Actor-InputComponent.md 'UnrealEngine.Framework.Actor.InputComponent')
- [IsRootComponentMovable](./Actor-IsRootComponentMovable.md 'UnrealEngine.Framework.Actor.IsRootComponentMovable')
- [IsSpawned](./Actor-IsSpawned.md 'UnrealEngine.Framework.Actor.IsSpawned')
- [Name](./Actor-Name.md 'UnrealEngine.Framework.Actor.Name')
### Methods
- [AddTag(string)](./Actor-AddTag(string).md 'UnrealEngine.Framework.Actor.AddTag(string)')
- [Destroy()](./Actor-Destroy().md 'UnrealEngine.Framework.Actor.Destroy()')
- [Equals(UnrealEngine.Framework.Actor)](./Actor-Equals(Actor).md 'UnrealEngine.Framework.Actor.Equals(UnrealEngine.Framework.Actor)')
- [ForEachAttachedActor&lt;T&gt;(System.Action&lt;T&gt;)](./Actor-ForEachAttachedActor-T-(Action-T-).md 'UnrealEngine.Framework.Actor.ForEachAttachedActor&lt;T&gt;(System.Action&lt;T&gt;)')
- [ForEachChildActor&lt;T&gt;(System.Action&lt;T&gt;)](./Actor-ForEachChildActor-T-(Action-T-).md 'UnrealEngine.Framework.Actor.ForEachChildActor&lt;T&gt;(System.Action&lt;T&gt;)')
- [ForEachComponent&lt;T&gt;(System.Action&lt;T&gt;)](./Actor-ForEachComponent-T-(Action-T-).md 'UnrealEngine.Framework.Actor.ForEachComponent&lt;T&gt;(System.Action&lt;T&gt;)')
- [ForEachOverlappingActor&lt;T&gt;(System.Action&lt;T&gt;)](./Actor-ForEachOverlappingActor-T-(Action-T-).md 'UnrealEngine.Framework.Actor.ForEachOverlappingActor&lt;T&gt;(System.Action&lt;T&gt;)')
- [GetBool(string, bool)](./Actor-GetBool(string_bool).md 'UnrealEngine.Framework.Actor.GetBool(string, bool)')
- [GetBounds(bool, System.Numerics.Vector3, System.Numerics.Vector3)](./Actor-GetBounds(bool_Vector3_Vector3).md 'UnrealEngine.Framework.Actor.GetBounds(bool, System.Numerics.Vector3, System.Numerics.Vector3)')
- [GetByte(string, byte)](./Actor-GetByte(string_byte).md 'UnrealEngine.Framework.Actor.GetByte(string, byte)')
- [GetComponent&lt;T&gt;(string)](./Actor-GetComponent-T-(string).md 'UnrealEngine.Framework.Actor.GetComponent&lt;T&gt;(string)')
- [GetComponentByID&lt;T&gt;(uint)](./Actor-GetComponentByID-T-(uint).md 'UnrealEngine.Framework.Actor.GetComponentByID&lt;T&gt;(uint)')
- [GetComponentByTag&lt;T&gt;(string)](./Actor-GetComponentByTag-T-(string).md 'UnrealEngine.Framework.Actor.GetComponentByTag&lt;T&gt;(string)')
- [GetDistanceTo(UnrealEngine.Framework.Actor)](./Actor-GetDistanceTo(Actor).md 'UnrealEngine.Framework.Actor.GetDistanceTo(UnrealEngine.Framework.Actor)')
- [GetDouble(string, double)](./Actor-GetDouble(string_double).md 'UnrealEngine.Framework.Actor.GetDouble(string, double)')
- [GetEnum&lt;T&gt;(string, T)](./Actor-GetEnum-T-(string_T).md 'UnrealEngine.Framework.Actor.GetEnum&lt;T&gt;(string, T)')
- [GetEyesViewPoint(System.Numerics.Vector3, System.Numerics.Quaternion)](./Actor-GetEyesViewPoint(Vector3_Quaternion).md 'UnrealEngine.Framework.Actor.GetEyesViewPoint(System.Numerics.Vector3, System.Numerics.Quaternion)')
- [GetFloat(string, float)](./Actor-GetFloat(string_float).md 'UnrealEngine.Framework.Actor.GetFloat(string, float)')
- [GetHashCode()](./Actor-GetHashCode().md 'UnrealEngine.Framework.Actor.GetHashCode()')
- [GetHorizontalDistanceTo(UnrealEngine.Framework.Actor)](./Actor-GetHorizontalDistanceTo(Actor).md 'UnrealEngine.Framework.Actor.GetHorizontalDistanceTo(UnrealEngine.Framework.Actor)')
- [GetInt(string, int)](./Actor-GetInt(string_int).md 'UnrealEngine.Framework.Actor.GetInt(string, int)')
- [GetLong(string, long)](./Actor-GetLong(string_long).md 'UnrealEngine.Framework.Actor.GetLong(string, long)')
- [GetRootComponent&lt;T&gt;()](./Actor-GetRootComponent-T-().md 'UnrealEngine.Framework.Actor.GetRootComponent&lt;T&gt;()')
- [GetShort(string, short)](./Actor-GetShort(string_short).md 'UnrealEngine.Framework.Actor.GetShort(string, short)')
- [GetText(string, string)](./Actor-GetText(string_string).md 'UnrealEngine.Framework.Actor.GetText(string, string)')
- [GetUInt(string, uint)](./Actor-GetUInt(string_uint).md 'UnrealEngine.Framework.Actor.GetUInt(string, uint)')
- [GetULong(string, ulong)](./Actor-GetULong(string_ulong).md 'UnrealEngine.Framework.Actor.GetULong(string, ulong)')
- [GetUShort(string, ushort)](./Actor-GetUShort(string_ushort).md 'UnrealEngine.Framework.Actor.GetUShort(string, ushort)')
- [HasTag(string)](./Actor-HasTag(string).md 'UnrealEngine.Framework.Actor.HasTag(string)')
- [Hide(bool)](./Actor-Hide(bool).md 'UnrealEngine.Framework.Actor.Hide(bool)')
- [Invoke(string)](./Actor-Invoke(string).md 'UnrealEngine.Framework.Actor.Invoke(string)')
- [IsOverlappingActor(UnrealEngine.Framework.Actor)](./Actor-IsOverlappingActor(Actor).md 'UnrealEngine.Framework.Actor.IsOverlappingActor(UnrealEngine.Framework.Actor)')
- [RegisterEvent(UnrealEngine.Framework.ActorEventType)](./Actor-RegisterEvent(ActorEventType).md 'UnrealEngine.Framework.Actor.RegisterEvent(UnrealEngine.Framework.ActorEventType)')
- [RemoveTag(string)](./Actor-RemoveTag(string).md 'UnrealEngine.Framework.Actor.RemoveTag(string)')
- [Rename(string)](./Actor-Rename(string).md 'UnrealEngine.Framework.Actor.Rename(string)')
- [SetBool(string, bool)](./Actor-SetBool(string_bool).md 'UnrealEngine.Framework.Actor.SetBool(string, bool)')
- [SetByte(string, byte)](./Actor-SetByte(string_byte).md 'UnrealEngine.Framework.Actor.SetByte(string, byte)')
- [SetDouble(string, double)](./Actor-SetDouble(string_double).md 'UnrealEngine.Framework.Actor.SetDouble(string, double)')
- [SetEnableCollision(bool)](./Actor-SetEnableCollision(bool).md 'UnrealEngine.Framework.Actor.SetEnableCollision(bool)')
- [SetEnableInput(UnrealEngine.Framework.PlayerController, bool)](./Actor-SetEnableInput(PlayerController_bool).md 'UnrealEngine.Framework.Actor.SetEnableInput(UnrealEngine.Framework.PlayerController, bool)')
- [SetEnum&lt;T&gt;(string, T)](./Actor-SetEnum-T-(string_T).md 'UnrealEngine.Framework.Actor.SetEnum&lt;T&gt;(string, T)')
- [SetFloat(string, float)](./Actor-SetFloat(string_float).md 'UnrealEngine.Framework.Actor.SetFloat(string, float)')
- [SetInt(string, int)](./Actor-SetInt(string_int).md 'UnrealEngine.Framework.Actor.SetInt(string, int)')
- [SetLifeSpan(float)](./Actor-SetLifeSpan(float).md 'UnrealEngine.Framework.Actor.SetLifeSpan(float)')
- [SetLong(string, long)](./Actor-SetLong(string_long).md 'UnrealEngine.Framework.Actor.SetLong(string, long)')
- [SetRootComponent(UnrealEngine.Framework.SceneComponent)](./Actor-SetRootComponent(SceneComponent).md 'UnrealEngine.Framework.Actor.SetRootComponent(UnrealEngine.Framework.SceneComponent)')
- [SetShort(string, short)](./Actor-SetShort(string_short).md 'UnrealEngine.Framework.Actor.SetShort(string, short)')
- [SetText(string, string)](./Actor-SetText(string_string).md 'UnrealEngine.Framework.Actor.SetText(string, string)')
- [SetUInt(string, uint)](./Actor-SetUInt(string_uint).md 'UnrealEngine.Framework.Actor.SetUInt(string, uint)')
- [SetULong(string, ulong)](./Actor-SetULong(string_ulong).md 'UnrealEngine.Framework.Actor.SetULong(string, ulong)')
- [SetUShort(string, ushort)](./Actor-SetUShort(string_ushort).md 'UnrealEngine.Framework.Actor.SetUShort(string, ushort)')
- [TeleportTo(System.Numerics.Vector3, System.Numerics.Quaternion, bool, bool)](./Actor-TeleportTo(Vector3_Quaternion_bool_bool).md 'UnrealEngine.Framework.Actor.TeleportTo(System.Numerics.Vector3, System.Numerics.Quaternion, bool, bool)')
- [UnregisterEvent(UnrealEngine.Framework.ActorEventType)](./Actor-UnregisterEvent(ActorEventType).md 'UnrealEngine.Framework.Actor.UnregisterEvent(UnrealEngine.Framework.ActorEventType)')
