# JRAlertView
  使用block替代UIAlertView的delegate。
  每次调用UIAlertView都要烦心地搞一下Delegate才行，故偷懒写了个UIAlertView的category减少工作量，再UIAlertView初始化的时候直接把回调写在block里面。
