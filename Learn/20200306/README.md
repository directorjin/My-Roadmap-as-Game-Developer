# My-Roadmap-as-Game-Developer
🗺️My Roadmap as Game-Developer
  
    
 <hr>
 
2020-03-06
=====

C#basic
----

1. internal class //내부적인 빌드안에서만 작동하는 클래스
2. public class //외부에서 빌드해서 dll 생성후 솔루션 익스플로러에서 가져오기를 통해서 해당 클래스를 사용할 수 있게됌
3. Dictionary //
Dictionary<string,string> cache; //key도 value도 string타입임.


4. Indexer //특정값만 바꿔줄 수 있음 파라미터가 있음
public string this[string key] //this가 인덱서의 핵심.
{
	get;
	set;
}


5. Property //전체를 바꿔줌 파라미터가 없음
public DataTime CacheExpires
{
	get {return cacheExpires;}
	set {cacheExpires = value;}
}
  
