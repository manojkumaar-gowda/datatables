# datatables

Hello guys, This is a demonstration of how Datatable works.
  
  Datatables is used to minimize the tasks of creating a custom table containing a search bar, limiting the number of results to be displayed in a page

Link for live demonstration: https://manojkumaar-gowda.github.io/datatables/

1. Create a html file and code so that you have a normal table as your output

2. If you wish to add Bootstrap you can create a bootstrap table too.

3. Now its time to add Datatables related files. In the head part of your html file add

    
    >> 
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    
    
    >> 
        <link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.11.3/css/jquery.dataTables.css">
    
    
    >> 
        <script type="text/javascript" charset="utf8" src="https://cdn.datatables.net/1.11.3/js/jquery.dataTables.js"></script>
    
    
    >> 
        <script>
        $(document).ready(function(){
		         $("#myTable").DataTable();
        });
   	    </script>
        
        
  4. Lastly, give your table an id. Since myTable has been used as id in the jquery part of your code use myTable. You can also give names of your choice



I am attaching a sample screenshot of the app

![image](https://user-images.githubusercontent.com/95869837/149780235-63ba31be-10e5-4fd2-99b7-c377f6fbc47b.png)

    
