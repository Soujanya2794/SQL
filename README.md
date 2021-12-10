select P.ProductID, P.Name, P.rowguid

from Production.Product P

inner join Sales.SalesOrderDetail D

on P.ProductID=D.ProductID

or P.rowguid=D.rowguid;
