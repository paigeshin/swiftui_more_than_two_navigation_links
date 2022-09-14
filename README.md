# swiftui_more_than_two_navigation_links

```swift
            Group {
                NavigationLink(isActive: $vm.navigateToRegister,
                               destination: { ModuleFactory.RegisterModule() },
                               label: {EmptyView()})
                .buttonStyle(PlainButtonStyle())
                
                NavigationLink(destination: EmptyView(), label: {})
                    .buttonStyle(PlainButtonStyle())
                
                NavigationLink(isActive: $vm.navigateToFindPasssword,
                               destination: { ModuleFactory.FindPasswordModule() },
                               label: {EmptyView()})
                .buttonStyle(PlainButtonStyle())
                
                NavigationLink(destination: EmptyView(), label: {})
                    .buttonStyle(PlainButtonStyle())
            }
            
```
