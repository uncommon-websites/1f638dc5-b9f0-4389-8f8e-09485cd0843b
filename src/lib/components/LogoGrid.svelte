<script>
    const logos = [
<<<<<<< HEAD
        { name: 'Salesforce', hasCaseStudy: false },
        { name: 'HubSpot', hasCaseStudy: false },
        { name: 'Stripe', hasCaseStudy: false },
        { name: 'Shopify', hasCaseStudy: false },
        { name: 'Atlassian', hasCaseStudy: false },
        { name: 'Zendesk', hasCaseStudy: false },
        { name: 'Slack', hasCaseStudy: false },
        { name: 'Mailchimp', hasCaseStudy: false },
        { name: 'Airtable', hasCaseStudy: false },
        { name: 'Notion', hasCaseStudy: false }
=======
        { name: 'Stripe', hasCaseStudy: false },
        { name: 'Notion', hasCaseStudy: false },
        { name: 'Slack', hasCaseStudy: false },
        { name: 'Figma', hasCaseStudy: false },
        { name: 'Airtable', hasCaseStudy: false },
        { name: 'Webflow', hasCaseStudy: false },
        { name: 'Intercom', hasCaseStudy: false },
        { name: 'Zapier', hasCaseStudy: false },
        { name: 'Miro', hasCaseStudy: false },
        { name: 'Asana', hasCaseStudy: false },
        { name: 'Monday', hasCaseStudy: false },
        { name: 'ClickUp', hasCaseStudy: false },
        { name: 'Loom', hasCaseStudy: false },
        { name: 'Canva', hasCaseStudy: false },
        { name: 'Dropbox', hasCaseStudy: false }
>>>>>>> 44c0cac6eebc7bb8c7d0258fbecb2b329bfdd697
    ];
</script>

<section class="py-12 bg-white border-b border-gray-200 font-sans">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <p class="text-center text-[10px] uppercase tracking-widest text-gray-500 font-bold mb-8">
<<<<<<< HEAD
            TRUSTED BY FORWARD-THINKING B2B BRANDS
=======
            Trusted by forward-thinking B2B teams preparing for AI-first search
>>>>>>> 44c0cac6eebc7bb8c7d0258fbecb2b329bfdd697
        </p>

        <div class="grid grid-cols-2 md:grid-cols-5 gap-0 border-t border-l border-gray-200">
            {#each logos as logo}
                <div class="flex items-center justify-center p-6 border-r border-b border-gray-200 h-24 relative group">
<<<<<<< HEAD
                    <span class="text-lg md:text-xl font-bold text-gray-300 group-hover:text-gray-600 transition-colors">
                        {logo.name}
                    </span>
=======
                    <!-- Logo Placeholder -->
                    <span class="text-lg md:text-xl font-semibold text-gray-300 group-hover:text-gray-700 transition-colors">
                        {logo.name}
                    </span>

                    {#if logo.hasCaseStudy}
                        <a href="#" class="absolute top-2 right-2 text-[8px] font-bold text-pink-600 bg-pink-50 px-1.5 py-0.5 rounded border border-pink-100 hover:bg-pink-100 flex items-center transition-colors">
                            {logo.caseStudyText} 
                            <svg class="w-2 h-2 ml-0.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
                        </a>
                    {/if}
>>>>>>> 44c0cac6eebc7bb8c7d0258fbecb2b329bfdd697
                </div>
            {/each}
        </div>
    </div>
</section>
