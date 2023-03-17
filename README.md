# book-api

Create a simple Java AWS lambda function which takes books xml as input from API Gateway request and saves them to DynamoDb table and to S3 bucket.

Books xml structure:
```
<books>
	<book>
		<title>Java</title>
		<author>Eckel</author>
		<year>2004</year>
		<pages>200</pages>
	</book>
	<book>
		<title>C#</title>
		<author>Schildt</author>
		<year>2003</year>
		<pages>800</pages>
	</book>
</books>
```
