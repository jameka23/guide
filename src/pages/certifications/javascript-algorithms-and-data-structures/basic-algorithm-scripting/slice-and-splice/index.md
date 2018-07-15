---
title: Slice and Splice
---
## Slice and Splice

function frankenSplice(arr1, arr2, n) {
  // It's alive. It's alive!
  var arrB=arr2.slice(0,arr2.length);
  //console.log(n);
  var num = arr2.indexOf(n);
  //console.log(num);
  for(var x=arr1.length-1;x>-1;x--){
    arrB.splice(n,0,arr1[x]);
  }

  return arrB;
}
frankenSplice([1, 2, 3], [4, 5, 6], 1);

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
