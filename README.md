# self.js
miu((self)=>( for(be in self){ promise(be).then((cell)=>( cell.bind(self,context.call))).promise().then(()=>) }))
