# sp-bootstrap-list-viewer

A Javascript plugin that will create a custom view for your SharePoint list. Complete with filtering and pagination. 

### Note that this will require the following files:

* jquery.min.js
* jquery.SPServices-2014.02.min.js
* bootstrap.min.css

### This plugin will include the above files via CDN

####How to use the plugin:

Note that I've only tested this with SharePoint 2013. You may need administrator rights to your website, as well as you should know how to work with custom lists and document libraries and such. 

After you have downloaded the files, open the "sp-bootstrap-list-viewer.html" in you text editor. This is where you will add the plugin information. You basically need to add 2 things: the list name, the "Answer" column. The rest of the options are optional such as the "filterBy" and "rowLimit". The table below will show you want the rest of the options do. 

![alt tag](http://michaelsoriano.com/wp-content/uploads/2015/07/sp-list3.jpg)

Once you have edited the html file, upload it to a location in your SharePoint site, typically a document library. You will need to copy the location of the file. 

![alt tag](http://michaelsoriano.com/wp-content/uploads/2015/07/sp-list2.jpg)

Let's go ahead and add a CEWP into your SharePoint page. in the "Content Link" input, add the location of the html file you've just uploaded. 

![alt tag](http://michaelsoriano.com/wp-content/uploads/2015/07/sp-list1.jpg)

Click "OK" and if everything is configured correctly, you should see the plugin do its thing:

![alt tag](http://i1.wp.com/michaelsoriano.com/wp-content/uploads/2015/07/sp-bootstrap-list-viewer.gif)

The table below contains the options for the plugin and an explanation of what they're for:

<table class="table table-bordered">
      <thead>
        <tr>
          <th>Option name</th>
          <th>Default Value</th>
          <th>Required?</th>
          <th>Description</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th>instance</th>
          <td>Random Value</td>
          <td>Yes</td>
          <td>Used as the "Id" of your plugin</td>
        </tr>
        <tr>
          <th>listName</th>
          <td>none</td>
          <td>Yes</td>
          <td>Name of the SP list</td>
        </tr>
        <tr>
          <th>question</th>
          <td>Title</td>
          <td>Yes</td>
          <td>Title of the row</td>
        </tr>
        <tr>
          <th>answer</th>
          <td>none</td>
          <td>Yes</td>
          <td>Body of the row</td>
        </tr>
        <tr>
          <th>filterBy</th>
          <td>none</td>
          <td>No</td>
          <td>Category column to filter rows</td>
        </tr>
        <tr>
          <th>rowLimit</th>
          <td>5</td>
          <td>No</td>
          <td>Number of rows to show</td>
        </tr>
      </tbody>
 </table>




For more details on how the plugin works, see my post: 
http://michaelsoriano.com/sharepoint-bootstrap-using-spservices-and-jquery/

THIS SOFTWARE IS PROVIDED "AS IS" AND ANY EXPRESSED OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE REGENTS OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

