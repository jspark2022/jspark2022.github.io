---
layout: post
title:  "JAVA Switch문 기초"
date: 2022-04-07 00:01:00
---

# JAVA Switch문 

**JAVA Switch문 **, 자바 swtich문 기초 사용법 입니다..

```java
package java_study;

public class switch_case_study {

	public static void main(String[] args) {
		// switch/case 문은 if 문과 비슷하지만 좀 더 정형화된 조건 판단문이다.
		
		
		// switch/case 문의 기본 구조
		/*
		 switch(입력변수) {
    		case 입력값1: ...
         		break;
		    case 입력값2: ...
		         break;
		    ...
		    default: ...
		         break;
		}
		 */
		
		//입력변수의 값과 일치하는 case 입력값이 있다면 해당 case문의 문장이 실행된다.
		//switch/case문 예시
	int month = 8;			//8이 입력 되었기 때문에 case 8에 해당하는 August가 출력된다
	String monthString = "";
	switch(month) {
	case 1:  monthString = "January";
	    break;
	case 2:  monthString = "February";
	    break;
	case 3:  monthString = "March";
	    break;
	case 4:  monthString = "April";
	    break;
	case 5:  monthString = "May";
	    break;
	case 6:  monthString = "June";
	    break;
	case 7:  monthString = "July";
	    break;
	case 8:  monthString = "August";
	    break;
	case 9:  monthString = "September";
	    break;
	case 10: monthString = "October";
	    break;
	case 11: monthString = "November";
	    break;
	case 12: monthString = "December";
	    break;
	default: monthString = "Invalid month";
	    break;
	}
	System.out.println(monthString);
		
	
	}

}

```
