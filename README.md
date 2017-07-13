# Test-Application
<Window x:Class="WpfGridView.MainWindow"
        xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
        xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
        xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
        xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
        xmlns:local="clr-namespace:WpfGridView"
        mc:Ignorable="d"
        Title="MainWindow" Height="750" Width="1300">

    <Grid>
        <ListView Margin="10" Name="Employees">
            <ListView.View>
                <GridView>
                    <GridViewColumn Header="Name" Width="120" DisplayMemberBinding="{Binding Name}" />
                    <GridViewColumn Header="Id" Width="50" DisplayMemberBinding="{Binding Id}" />
                    
                    <GridViewColumn Header="JobProfile" Width="150" DisplayMemberBinding="{Binding JobProfile}" />
                    <GridViewColumn Header="Qualification" Width="150" DisplayMemberBinding="{Binding Qualification}" />
                    <GridViewColumn Header="CollegeName" Width="150" DisplayMemberBinding="{Binding CollegeName}" />
                   
                    <GridViewColumn Header="PermanentAddress" Width="150" DisplayMemberBinding="{Binding PermanentAddress}" />
                    <GridViewColumn Header="Mail Id" Width="150" DisplayMemberBinding="{Binding MailId}" />
                    <GridViewColumn Header="MobileNo" Width="150" DisplayMemberBinding="{Binding MobileNo}" />
                </GridView>
            </ListView.View>
        </ListView>











    </Grid>
</Window>
