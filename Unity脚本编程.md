Void Start 初始化在游戏开始时运行一次  
Void Update 每帧刷新  
修改物体位移方法: Transform.Translate();  
修改物体旋转方法: Transform.Rotate();  

void Start()  
{  
  //获取到组件后，将它的引用保存在collider字段中，方便下次使用  
  collider = gameObject.GetComponent<SphereCollider>();  
  }  
}
