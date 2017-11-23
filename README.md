<?xml version="1.0" encoding="utf-8"?>
<xs:schema attributeFormDefault="unqualified" elementFormDefault="qualified" xmlns:xs="http://www.w3.org/2001/XMLSchema">
  <xs:element name="Coaches">
    <xs:complexType>
      <xs:sequence>
        <xs:element name="Coach" maxOccurs="unbounded" minOccurs="0">
          <xs:complexType>
            <xs:sequence>
              <xs:element name="Player">
                <xs:complexType>
                  <xs:sequence>
                    <xs:element type="xs:string" name="Name"/>
                    <xs:element type="xs:string" name="Surname"/>
                  </xs:sequence>
                </xs:complexType>
              </xs:element>
              <xs:element name="Personal">
                <xs:complexType>
                  <xs:sequence>
                    <xs:element type="xs:string" name="Name"/>
                    <xs:element type="xs:string" name="Surname"/>
                    <xs:element type="xs:byte" name="Age"/>
                    <xs:element type="xs:string" name="Country"/>
                    <xs:element type="xs:byte" name="Experience"/>
                  </xs:sequence>
                </xs:complexType>
              </xs:element>
            </xs:sequence>
          </xs:complexType>
        </xs:element>
      </xs:sequence>
    </xs:complexType>
  </xs:element>
</xs:schema>
