# java.util

## Collection & Map
### List
### Map

|方法|意义|
|-|-|
|void	clear() |从此映射中移除所有映射关系（可选操作）。|
| boolean	containsKey(Object key) | 如果此映射包含指定键的映射关系，则返回 true。|
|boolean	containsValue(Object value) |如果此映射将一个或多个键映射到指定值，则返回 true。|
| Set	entrySet() | 返回此映射中包含的映射关系的 Set 视图。|
| boolean	equals(Object o) | 比较指定的对象与此映射是否相等。|
| V	get(Object key) |返回指定键所映射的值；如果此映射不包含该键的映射关系，则返回 null。|
| int	hashCode() | 返回此映射的哈希码值。|
| boolean	isEmpty() |如果此映射未包含键-值映射关系，则返回 true。|
|Set|	keySet() |返回此映射中包含的键的 Set 视图。|
|V	|put(K key, V value) |将指定的值与此映射中的指定键关联（可选操作）。|

 void	putAll(Map<? extends K,? extends V> m) 
          从指定映射中将所有映射关系复制到此映射中（可选操作）。
 V	remove(Object key) 
          如果存在一个键的映射关系，则将其从此映射中移除（可选操作）。
 int	size() 
          返回此映射中的键-值映射关系数。
 Collection<V>	values() 
          返回此映射中包含的值的 Collection 视图。
#### Map.Entity
- Map.Entity Map的组成元素，一个Entity是一个键值对
#### HashMap
#####HashMapEntity
- HashMap.Entity是Map.Entity接口在HashMap中的实现，他是一个Entity也是一个链表的Node，他除了储存键值对之外，也储存下一个Entity信息。这样做的目的是为了解决Bucket冲突。
#### SortedMap
### Set
#### SortedSet



