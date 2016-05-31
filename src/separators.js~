'use strict';

function thousands_separators(num) {
        num=num.toString();
	var counter=0;
	var result="";
	var str1=num.split(".",1);
	str1=str1.toString();
	var str2=num.substr(num.indexOf("."));
	for(var i=str1.length-1;i>=0;i--)
	{
		counter++;
		result=str1.charAt(i)+result;
		if(!(counter%3) && i!=0)
		{
			result=","+result;
		}
	}
	if(num.indexOf(".")==-1)
		return result;
	else
		return result+str2;
}

module.exports = thousands_separators;
