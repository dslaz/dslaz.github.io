<StackPanel>   
    <Button Content="Submit" 
            Click="submitButtonClick"/>
    <TextBlock x:Name="textBlock1"/>
</StackPanel

Example Button
    <button Click="eventhandler"/>
    
If XAML
    <StackPanel>   
    <Button Content="Submit" 
            Click="submitButtonClick"/>
    <TextBlock x:Name="textBlock1"/>
</StackPanel>
    
If C#
    void submitButtonClick(object sender, RoutedEventArgs e)
{
    textBlock1.Text = "You clicked the Submit button.";
}
    
