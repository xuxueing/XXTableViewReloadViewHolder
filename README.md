[![Reference Status](https://www.versioneye.com/objective-c/reachability/reference_badge.svg?style=flat)](https://www.versioneye.com/objective-c/reachability/references)

# XXTableViewReloadViewHolder

这是一个非常简单的tableview分类  用法很简单 没有侵入性 只需拷贝到项目中 就可以 不破坏原来的tableview 不需要继承tableview

用途就是仿照微信QQ断网 在tableview上提示 自动监测  自动显示 自动消失

安装十分简单 只需 pod 'XXTableViewReloadViewHolder', '~> 1.0.0' 
或者clone下来拷贝到项目中
建议用pod

## Examples

### Block Example



#### In Objective-C

```objc
#import <UITableView+XXTableViewReloadViewHolder.h>
 self.tableView.enableShowNet = YES;
 self.tableView.enableShowNet = YES;
    self.tableView.enableShowError = YES;
    [self.tableView setPlaceHolderViewAction:^(id sender){
        
    }];
    [self.tableView setNoNetViewAction:^(id sender){
        
    }];

```



## Tell the world

如果喜欢 请点个star
