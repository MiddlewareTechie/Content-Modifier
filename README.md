# Content Modifier

The Content Modifier in SAP Cloud Integration serves as a versatile tool for managing message content during integration processes. It allows users to manipulate various aspects of message handling, including headers, properties, and the message body. Here’s a breakdown of the source types mentioned in your query:

Source Types in Content Modifier

Expression: This allows users to set values dynamically based on certain conditions or calculations. For example, you can use simple expressions to format dates or manipulate strings within headers or properties.

Global Variable: Global variables are accessible across different integration flows and can store data that needs to be shared among various components of the integration process.

Header: Headers are used to pass metadata about the message. They can be set with values derived from input data, making them crucial for effective integration flows. Headers can be exposed or kept internal based on configuration settings.

Local Variable: Local variables are confined to the specific integration flow and are not accessible outside of it. They are useful for temporary storage of data that does not need to persist beyond the flow's execution.

Number Range: This feature helps in generating unique sequence numbers within the message flow, which can be essential for tracking or identifying messages uniquely.

Property: Properties are internal message elements that do not propagate to the receiving system. They are retained within the integration flow and can be used for storing temporary data or state information.

XPath: XPath expressions are utilized for querying and transforming XML data within the Content Modifier. This allows for precise manipulation of XML structures, enabling users to extract or modify data as required.
The Content Modifier is structured into several sections: General, Headers, Properties, and Body, each serving a distinct purpose in managing the message content effectively. For instance, headers can be set with values from input data, while properties can be used to store process-related data that remains internal to the integration flow
