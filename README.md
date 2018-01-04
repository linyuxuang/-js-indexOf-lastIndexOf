# -js-indexOf-lastIndexOf
indexOf与lastIndexOf的用法

   indexOf() 和 lastIndexOf() 方法返回的都是指定的子串在另一个字符串中的位置，如果没有找不到子串，则返回 -1。 
   这两个方法的不同之处在于，indexOf() 方法是从字符串的开头（位置 0）开始检索字符串，而 lastIndexOf() 方法则是从字符串的结尾开始检索子串。





                      var colo=[1,2,3,4,5,6,7,8,9];
                       输出  [1, 2, 3, 4, 5, 6, 7, 8, 9]
                      console.log(colo)  

                       输出 -1  因为indexOf从前开始检索, 这里代表(第一个参数要检索的值,第二个是要开始检索的位置)
                     console.log(colo.indexOf(3,3))    

                     输出  2  lastIndexOf是后面开始检索, 里面参数和indexOf含义一样
                     console.log(colo.lastIndexOf(3,5))   

