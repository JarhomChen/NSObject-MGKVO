# https---github.com-JarhomChen-MGKVO

    
    
    //监听方法
    [self listenObj:user keyPath:@"flowers" response:^(id oldValue, id newValue) {
        //do something here
    }];

    //取消所有对象监听
    [self unListenAll];
    //取消某个被监听对象的所有监听
    [self unListenObj:user keyPath:nil];
    //取消某个对象的某个keypath监听
    [self unListenObj:user keyPath:@"loginUser"];
