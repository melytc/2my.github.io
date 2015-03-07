---
title: "Java sql type mapping (Oracle, MySql++)"
categories: [xml, db]
layout: "post"
date: "2008-04-18 11:16:00"
updated: "2008-08-04 07:53:26"
blogger:
    siteid: "7706585097329252419"
    postid: "6919979651931016465"
---

I found this useful table at the <a href="http://www.castor.org/ddlgen-mapping.html">castor</a> site:

<table border="0" cellpadding="2" cellspacing="1" width="100%"><tbody><tr><td><table border="0" cellpadding="8" cellspacing="1" width="100%"><caption>

</caption><tbody><tr class="cheader"><td class="cheader">Castor Type</td><td class="cheader">JDBC Type</td><td class="cheader">Java Object Type</td><td class="cheader">MySQL</td><td class="cheader">PostgreSQL</td><td class="cheader">Oracle</td><td class="cheader">Derby</td><td class="cheader">MSSQL</td><td class="cheader">SapDB</td><td class="cheader">DB2</td><td class="cheader">Sybase</td><td class="cheader">HSQL</td><td class="cheader">PointBase</td></tr><tr bg="" style="color: rgb(221, 221, 221);">          <td><span class="bodyGrey">BIT</span></td>          <td><span class="bodyGrey">BIT</span></td>          <td><span class="bodyGrey">java.lang.Boolean</span></td>          <td><span class="bodyGrey">TINYINT(1)</span></td>          <td><span class="bodyGrey">BOOLEAN</span></td>          <td><span class="bodyGrey">BOOLEAN</span></td>          <td><span class="bodyGrey">CHAR FOR BIT DATA</span></td>          <td><span class="bodyGrey">BIT</span></td>          <td><span class="bodyGrey">BOOLEAN</span></td>          <td><span class="bodyGrey">

</span></td>          <td><span class="bodyGrey">BIT</span></td>          <td><span class="bodyGrey">BIT</span></td>          <td><span class="bodyGrey">BOOLEAN</span></td>        </tr><tr bg="" style="color: rgb(255, 255, 255);">          <td><span class="bodyGrey">TINYINT</span></td>          <td><span class="bodyGrey">TINYINT</span></td>          <td><span class="bodyGrey">java.lang.Byte</span></td>          <td><span class="bodyGrey">TINYINT</span></td>          <td><span class="bodyGrey">SMALLINT</span></td>          <td><span class="bodyGrey">SMALLINT</span></td>          <td><span class="bodyGrey">SMALLINT</span></td>          <td><span class="bodyGrey">TINYINT</span></td>          <td><span class="bodyGrey">SMALLINT</span></td>          <td><span class="bodyGrey">SMALLINT</span></td>          <td><span class="bodyGrey">TINYINT</span></td>          <td><span class="bodyGrey">TINYINT</span></td>          <td><span class="bodyGrey">SMALLINT</span></td>        </tr><tr bg="" style="color: rgb(221, 221, 221);">          <td><span class="bodyGrey">SMALLINT</span></td>          <td><span class="bodyGrey">SMALLINT</span></td>          <td><span class="bodyGrey">java.lang.Short</span></td>          <td><span class="bodyGrey">SMALLINT</span></td>          <td><span class="bodyGrey">SMALLINT</span></td>          <td><span class="bodyGrey">SMALLINT</span></td>          <td><span class="bodyGrey">SMALLINT</span></td>          <td><span class="bodyGrey">SMALLINT</span></td>          <td><span class="bodyGrey">SMALLINT</span></td>          <td><span class="bodyGrey">SMALLINT</span></td>          <td><span class="bodyGrey">SMALLINT</span></td>          <td><span class="bodyGrey">SMALLINT</span></td>          <td><span class="bodyGrey">SMALLINT</span></td>        </tr><tr bg="" style="color: rgb(255, 255, 255);">          <td><span class="bodyGrey">INTEGER</span></td>          <td><span class="bodyGrey">INTEGER</span></td>          <td><span class="bodyGrey">java.lang.Integer</span></td>          <td><span class="bodyGrey">INTEGER</span></td>          <td><span class="bodyGrey">INTEGER</span></td>          <td><span class="bodyGrey">INTEGER</span></td>          <td><span class="bodyGrey">INTEGER</span></td>          <td><span class="bodyGrey">INTEGER</span></td>          <td><span class="bodyGrey">INTEGER</span></td>          <td><span class="bodyGrey">INTEGER</span></td>          <td><span class="bodyGrey">INTEGER</span></td>          <td><span class="bodyGrey">INTEGER</span></td>          <td><span class="bodyGrey">INTEGER</span></td>        </tr><tr bg="" style="color: rgb(221, 221, 221);">          <td><span class="bodyGrey">BIGINT</span></td>          <td><span class="bodyGrey">BIGINT</span></td>          <td><span class="bodyGrey">java.lang.Long</span></td>          <td><span class="bodyGrey">BIGINT</span></td>          <td><span class="bodyGrey">BIGINT</span></td>          <td><span class="bodyGrey">NUMERIC</span></td>          <td><span class="bodyGrey">BIGINT</span></td>          <td><span class="bodyGrey">BIGINT</span></td>          <td><span class="bodyGrey">INTEGER</span></td>          <td><span class="bodyGrey">BIGINT</span></td>          <td><span class="bodyGrey">INTEGER</span></td>          <td><span class="bodyGrey">BIGINT</span></td>          <td><span class="bodyGrey">NUMERIC</span></td>        </tr><tr bg="" style="color: rgb(255, 255, 255);">          <td><span class="bodyGrey">FLOAT</span></td>          <td><span class="bodyGrey">FLOAT</span></td>          <td><span class="bodyGrey">java.lang.Double</span></td>          <td><span class="bodyGrey">FLOAT</span></td>          <td><span class="bodyGrey">DOUBLE PRECISION</span></td>          <td><span class="bodyGrey">FLOAT</span></td>          <td><span class="bodyGrey">FLOAT</span></td>          <td><span class="bodyGrey">FLOAT</span></td>          <td><span class="bodyGrey">FLOAT</span></td>          <td><span class="bodyGrey">FLOAT</span></td>          <td><span class="bodyGrey">FLOAT</span></td>          <td><span class="bodyGrey">FLOAT</span></td>          <td><span class="bodyGrey">FLOAT</span></td>        </tr><tr bg="" style="color: rgb(221, 221, 221);">          <td><span class="bodyGrey">DOUBLE</span></td>          <td><span class="bodyGrey">DOUBLE</span></td>          <td><span class="bodyGrey">java.lang.Double</span></td>          <td><span class="bodyGrey">DOUBLE</span></td>          <td><span class="bodyGrey">DOUBLE PRECISION</span></td>          <td><span class="bodyGrey">DOUBLE PRECISION</span></td>          <td><span class="bodyGrey">DOUBLE</span></td>          <td><span class="bodyGrey">DOUBLE PRECISION</span></td>          <td><span class="bodyGrey">DOUBLE PRECISION</span></td>          <td><span class="bodyGrey">DOUBLE</span></td>          <td><span class="bodyGrey">DOUBLE PRECISION</span></td>          <td><span class="bodyGrey">DOUBLE PRECISION</span></td>          <td><span class="bodyGrey">DOUBLE PRECISION</span></td>        </tr><tr bg="" style="color: rgb(255, 255, 255);">          <td><span class="bodyGrey">REAL</span></td>          <td><span class="bodyGrey">REAL</span></td>          <td><span class="bodyGrey">java.lang.Float</span></td>          <td><span class="bodyGrey">REAL</span></td>          <td><span class="bodyGrey">REAL</span></td>          <td><span class="bodyGrey">REAL</span></td>          <td><span class="bodyGrey">REAL</span></td>          <td><span class="bodyGrey">REAL</span></td>          <td><span class="bodyGrey">DOUBLE PRECISION</span></td>          <td><span class="bodyGrey">REAL</span></td>          <td><span class="bodyGrey">REAL</span></td>          <td><span class="bodyGrey">REAL</span></td>          <td><span class="bodyGrey">REAL</span></td>        </tr><tr bg="" style="color: rgb(221, 221, 221);">          <td><span class="bodyGrey">NUMERIC</span></td>          <td><span class="bodyGrey">NUMERIC</span></td>          <td><span class="bodyGrey">java.math.BigDecimal</span></td>          <td><span class="bodyGrey">NUMERIC</span></td>          <td><span class="bodyGrey">NUMERIC</span></td>          <td><span class="bodyGrey">NUMERIC</span></td>          <td><span class="bodyGrey">NUMERIC</span></td>          <td><span class="bodyGrey">NUMERIC</span></td>          <td><span class="bodyGrey">NUMERIC</span></td>          <td><span class="bodyGrey">NUMERIC</span></td>          <td><span class="bodyGrey">NUMERIC</span></td>          <td><span class="bodyGrey">NUMERIC</span></td>          <td><span class="bodyGrey">NUMERIC</span></td>        </tr><tr bg="" style="color: rgb(255, 255, 255);">          <td><span class="bodyGrey">DECIMAL</span></td>          <td><span class="bodyGrey">DECIMAL</span></td>          <td><span class="bodyGrey">java.math.BigDecimal</span></td>          <td><span class="bodyGrey">DECIMAL</span></td>          <td><span class="bodyGrey">NUMERIC</span></td>          <td><span class="bodyGrey">DECIMAL</span></td>          <td><span class="bodyGrey">DECIMAL</span></td>          <td><span class="bodyGrey">DECIMAL</span></td>          <td><span class="bodyGrey">DECIMAL</span></td>          <td><span class="bodyGrey">DECIMAL</span></td>          <td><span class="bodyGrey">DECIMAL</span></td>          <td><span class="bodyGrey">DECIMAL</span></td>          <td><span class="bodyGrey">DECIMAL</span></td>        </tr><tr bg="" style="color: rgb(221, 221, 221);">          <td><span class="bodyGrey">CHAR</span></td>          <td><span class="bodyGrey">CHAR</span></td>          <td><span class="bodyGrey">java.lang.String</span></td>          <td><span class="bodyGrey">CHAR</span></td>          <td><span class="bodyGrey">CHAR</span></td>          <td><span class="bodyGrey">CHAR</span></td>          <td><span class="bodyGrey">CHAR</span></td>          <td><span class="bodyGrey">CHAR</span></td>          <td><span class="bodyGrey">CHAR</span></td>          <td><span class="bodyGrey">CHAR</span></td>          <td><span class="bodyGrey">CHAR</span></td>          <td><span class="bodyGrey">CHAR</span></td>          <td><span class="bodyGrey">CHAR</span></td>        </tr><tr bg="" style="color: rgb(255, 255, 255);">          <td><span class="bodyGrey">VARCHAR</span></td>          <td><span class="bodyGrey">VARCHAR</span></td>          <td><span class="bodyGrey">java.lang.String</span></td>          <td><span class="bodyGrey">VARCHAR</span></td>          <td><span class="bodyGrey">VARCHAR</span></td>          <td><span class="bodyGrey">VARCHAR2</span></td>          <td><span class="bodyGrey">VARCHAR</span></td>          <td><span class="bodyGrey">VARCHAR</span></td>          <td><span class="bodyGrey">VARCHAR</span></td>          <td><span class="bodyGrey">VARCHAR</span></td>          <td><span class="bodyGrey">VARCHAR</span></td>          <td><span class="bodyGrey">VARCHAR</span></td>          <td><span class="bodyGrey">VARCHAR</span></td>        </tr><tr bg="" style="color: rgb(221, 221, 221);">          <td><span class="bodyGrey">DATE</span></td>          <td><span class="bodyGrey">DATE</span></td>          <td><span class="bodyGrey">java.sql.Date</span></td>          <td><span class="bodyGrey">DATE</span></td>          <td><span class="bodyGrey">DATE</span></td>          <td><span class="bodyGrey">DATE</span></td>          <td><span class="bodyGrey">DATE</span></td>          <td><span class="bodyGrey">DATETIME</span></td>          <td><span class="bodyGrey">DATE</span></td>          <td><span class="bodyGrey">DATE</span></td>          <td><span class="bodyGrey">DATETIME</span></td>          <td><span class="bodyGrey">DATE</span></td>          <td><span class="bodyGrey">DATE</span></td>        </tr><tr bg="" style="color: rgb(255, 255, 255);">          <td><span class="bodyGrey">TIME</span></td>          <td><span class="bodyGrey">TIME</span></td>          <td><span class="bodyGrey">java.sql.Time</span></td>          <td><span class="bodyGrey">TIME</span></td>          <td><span class="bodyGrey">TIME</span></td>          <td><span class="bodyGrey">DATE</span></td>          <td><span class="bodyGrey">TIME</span></td>          <td><span class="bodyGrey">DATETIME</span></td>          <td><span class="bodyGrey">TIME</span></td>          <td><span class="bodyGrey">TIME</span></td>          <td><span class="bodyGrey">DATETIME</span></td>          <td><span class="bodyGrey">TIME</span></td>          <td><span class="bodyGrey">TIME</span></td>        </tr><tr bg="" style="color: rgb(221, 221, 221);">          <td><span class="bodyGrey">TIMESTAMP</span></td>          <td><span class="bodyGrey">TIMESTAMP</span></td>          <td><span class="bodyGrey">java.sql.Timestamp</span></td>          <td><span class="bodyGrey">TIMESTAMP</span></td>          <td><span class="bodyGrey">TIMESTAMP</span></td>          <td><span class="bodyGrey">TIMESTAMP</span></td>          <td><span class="bodyGrey">TIMESTAMP</span></td>          <td><span class="bodyGrey">TIMESTAMP</span></td>          <td><span class="bodyGrey">TIMESTAMP</span></td>          <td><span class="bodyGrey">TIMESTAMP</span></td>          <td><span class="bodyGrey">TIMESTAMP</span></td>          <td><span class="bodyGrey">TIMESTAMP</span></td>          <td><span class="bodyGrey">TIMESTAMP</span></td>        </tr><tr bg="" style="color: rgb(255, 255, 255);">          <td><span class="bodyGrey">BINARY</span></td>          <td><span class="bodyGrey">BINARY</span></td>          <td><span class="bodyGrey">byte[]</span></td>          <td><span class="bodyGrey">BINARY</span></td>          <td><span class="bodyGrey">BYTEA</span></td>          <td><span class="bodyGrey">RAW</span></td>          <td><span class="bodyGrey">CHAR [n] FOR BIT DATA</span></td>          <td><span class="bodyGrey">BINARY</span></td>          <td><span class="bodyGrey">BLOB</span></td>          <td><span class="bodyGrey">CHAR [n] FOR BIT DATA</span></td>          <td><span class="bodyGrey">BINARY</span></td>          <td><span class="bodyGrey">BINARY</span></td>          <td><span class="bodyGrey">BLOB</span></td>        </tr><tr bg="" style="color: rgb(221, 221, 221);">          <td><span class="bodyGrey">VARBINARY</span></td>          <td><span class="bodyGrey">VARBINARY</span></td>          <td><span class="bodyGrey">byte[]</span></td>          <td><span class="bodyGrey">VARBINARY</span></td>          <td><span class="bodyGrey">BYTEA</span></td>          <td><span class="bodyGrey">LONG RAW</span></td>          <td><span class="bodyGrey">VARCHAR [] FOR BIT DATA</span></td>          <td><span class="bodyGrey">VARBINARY</span></td>          <td><span class="bodyGrey">BLOB</span></td>          <td><span class="bodyGrey">VARCHAR [] FOR BIT DATA</span></td>          <td><span class="bodyGrey">VARBINARY</span></td>          <td><span class="bodyGrey">VARBINARY</span></td>          <td><span class="bodyGrey">BLOB</span></td>        </tr><tr bg="" style="color: rgb(255, 255, 255);">          <td><span class="bodyGrey">LONGVARBINARY</span></td>          <td><span class="bodyGrey">LONGVARBINARY</span></td>          <td><span class="bodyGrey">byte[]</span></td>          <td><span class="bodyGrey">VARBINARY</span></td>          <td><span class="bodyGrey">BYTEA</span></td>          <td><span class="bodyGrey">LONG RAW</span></td>          <td><span class="bodyGrey">LONG VARCHAR FOR BIT DATA</span></td>          <td><span class="bodyGrey">IMAGE</span></td>          <td><span class="bodyGrey">BLOB</span></td>          <td><span class="bodyGrey">LONG VARCHAR FOR BIT DATA</span></td>          <td><span class="bodyGrey">VARBINARY</span></td>          <td><span class="bodyGrey">LONGVARBINARY</span></td>          <td><span class="bodyGrey">BLOB</span></td>        </tr><tr bg="" style="color: rgb(221, 221, 221);">          <td><span class="bodyGrey">OTHER</span></td>          <td><span class="bodyGrey">OTHER</span></td>          <td><span class="bodyGrey">java.lang.Object</span></td>          <td><span class="bodyGrey">BLOB</span></td>          <td><span class="bodyGrey">BYTEA</span></td>          <td><span class="bodyGrey">BLOB</span></td>          <td><span class="bodyGrey">BLOB</span></td>          <td><span class="bodyGrey">IMAGE</span></td>          <td><span class="bodyGrey">BLOB</span></td>          <td><span class="bodyGrey">BLOB</span></td>          <td><span class="bodyGrey">IMAGE</span></td>          <td><span class="bodyGrey">OTHER</span></td>          <td><span class="bodyGrey">BLOB</span></td>        </tr><tr bg="" style="color: rgb(255, 255, 255);">          <td><span class="bodyGrey">JAVA_OBJECT</span></td>          <td><span class="bodyGrey">JAVA_OBJECT</span></td>          <td><span class="bodyGrey">java.lang.Object</span></td>          <td><span class="bodyGrey">BLOB</span></td>          <td><span class="bodyGrey">BYTEA</span></td>          <td><span class="bodyGrey">BLOB</span></td>          <td><span class="bodyGrey">BLOB</span></td>          <td><span class="bodyGrey">IMAGE</span></td>          <td><span class="bodyGrey">BLOB</span></td>          <td><span class="bodyGrey">BLOB</span></td>          <td><span class="bodyGrey">IMAGE</span></td>          <td><span class="bodyGrey">OBJECT</span></td>          <td><span class="bodyGrey">BLOB</span></td>        </tr><tr bg="" style="color: rgb(221, 221, 221);">          <td><span class="bodyGrey">BLOB</span></td>          <td><span class="bodyGrey">BLOB</span></td>          <td><span class="bodyGrey">java.io.InputStream</span></td>          <td><span class="bodyGrey">BLOB</span></td>          <td><span class="bodyGrey">BYTEA</span></td>          <td><span class="bodyGrey">BLOB</span></td>          <td><span class="bodyGrey">BLOB</span></td>          <td><span class="bodyGrey">IMAGE</span></td>          <td><span class="bodyGrey">BLOB</span></td>          <td><span class="bodyGrey">BLOB</span></td>          <td><span class="bodyGrey">IMAGE</span></td>          <td><span class="bodyGrey">OBJECT</span></td>          <td><span class="bodyGrey">BLOB</span></td>        </tr><tr bg="" style="color: rgb(255, 255, 255);">          <td><span class="bodyGrey">CLOB</span></td>          <td><span class="bodyGrey">CLOB</span></td>          <td><span class="bodyGrey">java.sql.Clob</span></td>          <td><span class="bodyGrey">TEXT</span></td>          <td><span class="bodyGrey">TEXT</span></td>          <td><span class="bodyGrey">CLOB</span></td>          <td><span class="bodyGrey">CLOB</span></td>          <td><span class="bodyGrey">TEXT</span></td>          <td><span class="bodyGrey">CLOB</span></td>          <td><span class="bodyGrey">CLOB</span></td>          <td><span class="bodyGrey">TEXT</span></td>          <td><span class="bodyGrey">OBJECT</span></td>          <td><span class="bodyGrey">CLOB</span></td>        </tr></tbody></table></td></tr></tbody></table>     <a name="JDBC-Types-not-supported-by-Castor">
## 

</a></div>
</div>